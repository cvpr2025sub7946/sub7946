# Anonymous repository for paper submission: CVPR 2025, paper ID 7946

# Supplementary Visual Results


## Demo Usage

We show several demo usage samples below, based on Gradio. When we are ready to open source the code, we will also open source the Gradio demo.

Users do not need to calculate 6-DoF parameters themselves. Instead, they only need to interact with this demo and can preview each step in real time.

Generally, user operations can be divided into two parts: unit partition and unit-wise setting.

- In the following case, we show a sample of the combination of 3 units. We choose the fire as the Unit-1 and the fox as Unit-2, leaving the background as Unit-0. The category of Unit-0/1/2 are then set as borderland/brush/drag. You can refer to the following video to see how to input parameters (including the 6-DoF parameters) to each unit.

<table>
  <tr>
    <td colspan="3"><img src="gif/usage_0.gif"></td>
  </tr>
</table>

- In the following case, we show a sample of only camera control, where the whole image is considered as Unit-0 (the borderland unit). 

<table>
  <tr>
    <td colspan="3"><img src="gif/usage_1.gif"></td>
  </tr>
</table>

- In the following case, we show a sample of dragging, where we choose the elephant as Unit-1 (drag-unit). 

<table>
  <tr>
    <td colspan="3"><img src="gif/usage_2.gif"></td>
  </tr>
</table>

- In the following case, we show a sample of motion brush, where we choose the smoke as Unit-1 (brush-unit). 

<table>
  <tr>
    <td colspan="3"><img src="gif/usage_3.gif"></td>
  </tr>
</table>


## Camera Control Comparison

As suggested, we show the comparison on camera control task. We can see that our control precision is significantly higher than that of comparative methods.


<table>
  <tr>
    <th width=25% style="text-align:center">Input & GT Preview</th>
    <th width=25% style="text-align:center">CameraCtrl</th>
    <th width=25% style="text-align:center">MotionCtrl</th>
    <th width=25% style="text-align:center">Ours</th>
  </tr>
  <tr>
    <td colspan="4" ><img src="gif/camera_comparison_20241001235955_compress.gif"></td>
  </tr>
  <tr>
    <td colspan="4" ><img src="gif/camera_comparison_20241002002519.gif"></td>
  </tr>
  <tr>
    <td colspan="4" ><img src="gif/camera_comparison_20241120010734_compress.gif"></td>
  </tr>
  <tr>
    <td colspan="4" ><img src="gif/camera_comparison_20241120014418_compress.gif"></td>
  </tr>
  <tr>
    <td colspan="4" ><img src="gif/camera_comparison_20241120034631.gif"></td>
  </tr>
  <tr>
    <td colspan="4" ><img src="gif/camera_comparison_20241120041540_compress.gif"></td>
  </tr>
</table>


## Experiment on another base model

To prove the adaptive nature of our method, we present some results on another base model, [Seaweed](https://jimeng.jianying.com/ai-tool/image/generate).


- Camera Control:


<table>
  <tr>
    <th width=34% style="text-align:center">Generated</th>
    <th width=34% style="text-align:center">Camera Control</th>
    <th width=33% style="text-align:center">Input Image</th>
  </tr>
  <tr>
    <td colspan="3" ><img src="gif/seaweed_camera_0_compress.gif"></td>
  </tr>
  <tr>
    <td colspan="3" ><img src="gif/seaweed_camera_3_compress.gif"></td>
  </tr>
  <tr>
    <td colspan="3" ><img src="gif/seaweed_camera_2_compress.gif"></td>
  </tr>
  <tr>
    <td colspan="3" ><img src="gif/seaweed_camera_4_compress.gif"></td>
  </tr>
</table>

- Dragging:


<table>
  <tr>
    <th width=34% style="text-align:center">Generated</th>
    <th width=34% style="text-align:center">Dragging Control</th>
    <th width=33% style="text-align:center">Input Image</th>
  </tr>
  <tr>
    <td colspan="3" ><img src="gif/seaweed_drag_3.gif"></td>
  </tr>
  <tr>
    <td colspan="3" ><img src="gif/seaweed_drag_0_compress.gif"></td>
  </tr>
  <tr>
    <td colspan="3" ><img src="gif/seaweed_drag_1_compress.gif"></td>
  </tr>
  <tr>
    <td colspan="3" ><img src="gif/seaweed_drag_2_compress.gif"></td>
  </tr>
</table>

- Motion Brush:


<table>
  <tr>
    <th width=34% style="text-align:center">Generated</th>
    <th width=34% style="text-align:center">Brush Mask</th>
    <th width=33% style="text-align:center">Input Image</th>
  </tr>
  <tr>
    <td colspan="3" ><img src="gif/seaweed_brush_0.gif"></td>
  </tr>
  <tr>
    <td colspan="3" ><img src="gif/seaweed_brush_1.gif"></td>
  </tr>
  <tr>
    <td colspan="3" ><img src="gif/seaweed_brush_2.gif"></td>
  </tr>
</table>
