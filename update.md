## Anonymous repository for paper submission: CVPR 2025, paper ID 7946

# Supplementary Visual Results


## Demo Usage

We show several demo usage samples below, based on Gradio. When we are ready to open source the code, we will also open source the Gradio demo.

Users do not need to calculate 6-DoF parameters themselves. Instead, they only need to interact with this demo and can preview each step in real time.

Generally, user operations can be divided into two parts: unit partition and unit-wise setting.

- In this case, we show a sample of the combination of 3 units. We choose the fire as the Unit-1 and the fox as Unit-2, leaving the background as Unit-0. The category of Unit-0/1/2 are then set as borderland/brush/drag. You can refer to the following video to see how to input parameters (including the 6-DoF parameters) to each unit.

<table>
  <tr>
    <td colspan="3"><img src="gif/usage_0.gif"></td>
  </tr>
</table>




We show our camera control results with ground truth preview here, which demonstrates our pixel-level control capabilities.

We also list the results of the comparing methods for the qualitative comparison. We can observe that our control precision is significantly higher than that of comparative methods.


