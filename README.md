## Optimizing-Video-Sessions-for-Poor-Connectivity-issues

-This project aims to develop a solution for optimizing video sessions for poor connectivity issues, using Video Processing techniques.
-This would greatly help teachers and students have a smooth teaching-learning experience.

### Proposed system for enhancing video sessions

- Faculties will have option to capture video feed in RGB colored format (as usual) or in Grayscale (to save network bandwidth)

- In case students receive RGB coloured video feed, they will have the following options:

    - directly watch the incoming coloured video (as usual) if network connectivity is good
    - watch the greyscale video simultaneously as the incoming video feed is converted to greyscale before rendering (save on network bandwidth)
    
- In case students receive grayscale video feed, they will have the following options:

    - directly watch the incoming grayscale video feed (save on network bandwidth)
    - watch the generated RGB coloured video from grayscale feed (save on network bandwidth at the expense of some computation)
 
 
### Demonstration

- Convert live video feed from webcam to grayscale.
- Generate coloured image from a grayscale image & then extend this to video feeds.

#### References
- https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_gui/py_video_display/py_video_display.html
- https://github.com/jantic/DeOldify.git
