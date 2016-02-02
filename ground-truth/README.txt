Annotations for NUS II image dataset.

The NUS II image dataset is divided in two part. The first part is the hand posture
alone and the second is the hand posture with human noise. We provide the annotations
for this dataset as:

Hand posture alone                     Hand posture with human noise
Images        Rectangles               Images             Rectangles      
a_NUSII.txt   a_NUSII_rect.txt         a_NUSIINoise.txt   a_NUSIINoise_rect.txt
b_NUSII.txt   b_NUSII_rect.txt         b_NUSIINoise.txt   b_NUSIINoise_rect.txt
c_NUSII.txt   c_NUSII_rect.txt         c_NUSIINoise.txt   c_NUSIINoise_rect.txt
d_NUSII.txt   d_NUSII_rect.txt         d_NUSIINoise.txt   d_NUSIINoise_rect.txt
e_NUSII.txt   e_NUSII_rect.txt         e_NUSIINoise.txt   e_NUSIINoise_rect.txt
f_NUSII.txt   f_NUSII_rect.txt         f_NUSIINoise.txt   f_NUSIINoise_rect.txt
g_NUSII.txt   g_NUSII_rect.txt         g_NUSIINoise.txt   g_NUSIINoise_rect.txt
h_NUSII.txt   h_NUSII_rect.txt         h_NUSIINoise.txt   h_NUSIINoise_rect.txt
i_NUSII.txt   i_NUSII_rect.txt         i_NUSIINoise.txt   i_NUSIINoise_rect.txt
j_NUSII.txt   j_NUSII_rect.txt         j_NUSIINoise.txt   j_NUSIINoise_rect.txt


The format used to define a rectangle in the annotations files is:

width height x y 

		+-----------------------------------------------+ X
		|                                               |
		|    (x,y)     width                            |
		|          +----------+                         |
		|          |          |                         |
		|          |          |                         |
		|  height  |          |                         |
		|          |          |                         |
		|          |          |                         |
		|          +----------+                         |
		|                                               |
		|                                               |
		|                                               |
		|                                               |
		|                                               |
		|                                               |
		+-----------------------------------------------+
		Y
