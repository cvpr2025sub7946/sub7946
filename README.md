# Anonymous repository for paper submission: CVPR 2025, paper ID 7946


## Dragging

- In the following samples, we **drag the movable objects (both translation/rotation; both single/multiple objects)** in the input image:


<table>
  <tr>
    <th width=34% style="text-align:center">Input Image</th>
    <th width=32% style="text-align:center">Object Dragging</th>
    <th width=34% style="text-align:center">Result</th>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/ast_drag.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/man.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/rolling_balls_1.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/ship_drag.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/two_ducks.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/dragon_drag.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/two_pigs.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/ufo_drag.gif"></td>
  </tr>
</table>


## Camera Movement

- In the following samples, we **only move the camera** for the input sample:


<table>
  <tr>
    <th width=34% style="text-align:center">Input Image</th>
    <th width=32% style="text-align:center">Camera Movement</th>
    <th width=34% style="text-align:center">Result</th>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/camera_0.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/camera_1.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/camera_2.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/camera_3.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/camera_4.gif"></td>
  </tr>
</table>


## Camera Movement + Dragging

- In the following samples, we **move the camera and drag the movable objects** in the input image:


<table>
  <tr>
    <th width=34% style="text-align:center">Input Image</th>
    <th width=32% style="text-align:center">Camera & Object Movement</th>
    <th width=34% style="text-align:center">Result</th>
  </tr>
  <tr>
    <td colspan="3" ><img src="gif/duck_run.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/jellyfish.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/moon_walk.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/polarbear2.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/chaiquan_drag.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/swan.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/wolf.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/ball.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/boat.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/cat.gif"></td>
  </tr>
</table>

## Motion Brush for Movable Objects

In the following samples, we **brush a  mask for movable objects** in the input image and only set a scalar motion strength:

<table>
  <tr>
    <th width=34% style="text-align:center">Input Image</th>
    <th width=32% style="text-align:center">Brush Mask</th>
    <th width=34% style="text-align:center">Result</th>
  </tr>
  <tr>
    <td colspan="3" ><img src="gif/make_cake.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/dog_wash.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/duck_stand.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/play_guitar.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/llama.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/dive.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/dog_run.gif"></td>
  </tr>
</table>


## Motion Brush for Visual Effects

In the following samples, we **brush a  mask for fluids** in the input image and only set a scalar motion strength:

<table>
  <tr>
    <th width=34% style="text-align:center">Input Image</th>
    <th width=32% style="text-align:center">Brush Mask</th>
    <th width=34% style="text-align:center">Result</th>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/chimney.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/explode.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/skeleton.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/steamship.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/wand.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/candle.gif"></td>
  </tr>
  <tr>
    <td colspan="3" ><img src="gif/bonfire.gif"></td>
  </tr>
</table>


## Comprehensive Usage for Creation


- 【Union】We use dragging, camera movement, and motion brush in one single sample. We mask the brush-unit as red and mask the drag-unit as green.

 
<table>
  <tr>
    <th width=33% style="text-align:center">Input Image & Mask</th>
    <th width=33% style="text-align:center">Controls</th>
    <th width=34% style="text-align:center">Result</th>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/union_cat.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/union_human.gif"></td>
  </tr>
</table>

- 【Hitchcock】We fix the foreground and dolly out the background, creating a Hitchcock-like camera movement effect.

<table>
  <tr>
    <th width=34% style="text-align:center">Input Image</th>
    <th width=32% style="text-align:center">Controls</th>
    <th width=34% style="text-align:center">Result</th>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/dolly_zoom_0.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/dolly_zoom_1.gif"></td>
  </tr>
</table>

- 【Surrounding Character】We move the camera around a character and always keep the main character in place, which creates a beautiful dynamic portrait video.

<table>
  <tr>
    <th width=34% style="text-align:center">Input Image</th>
    <th width=32% style="text-align:center">Controls</th>
    <th width=34% style="text-align:center">Result</th>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/surrounding_0.gif"></td>
  </tr>
  <tr>
    <td colspan="3"><img src="gif/surrounding_1.gif"></td>
  </tr>
</table>


- 【Flowing Hair】We consider the whole image as borderland, set a motion strength, and set the prompt as "flowing in the wind". Then the artistic portraits can have some dynamics.

<table>
  <tr>
    <th width=25% style="text-align:center">Input Image</th>
    <th width=25% style="text-align:center">Result</th>
    <th width=25% style="text-align:center">Input Image</th>
    <th width=25% style="text-align:center">Result</th>
  </tr>
  <tr>
    <td colspan="2"><img src="gif/hair_0.gif"></td>
    <td colspan="2"><img src="gif/hair_1.gif"></td>
  </tr>
  <tr>
    <td colspan="2"><img src="gif/hair_2.gif"></td>
    <td colspan="2"><img src="gif/hair_3.gif"></td>
  </tr>
</table>

