# Waldo_handling
Scripts and tools for handling paired imagery from Waldo camera pods

Screenshots below show "overlap zones" of paired photographs (simultaneous imagery from paired cameras, overlapping in the interior margin). Colored lines represent tie points automatically detected between the photographs using the ORB algorithm in the notebook provided. These tie points are used with image and camera parameters to estimate the size of the overlap zone (in pixels) and the angle of overlap between the camera's fields-of-view, assuming that the cameras are mounted in-line with symetric horizontal angular offsets.

Future improvements may explore the use of alternative keypoint generating algorithms (SIFT, FAST, etc.) and more dynamic parameters for filtering potential ties.
![screenshot of automatic tie points in overlap zones](https://raw.githubusercontent.com/gl7176/Waldo_handling/refs/heads/main/matches_screenshot_10.12.2024.png) ![screenshot of automatic tie points in overlap zones](https://raw.githubusercontent.com/gl7176/Waldo_handling/refs/heads/main/matches_screenshot_10.12.2024b.png) ![screenshot of automatic tie points in overlap zones](https://raw.githubusercontent.com/gl7176/Waldo_handling/refs/heads/main/matches_screenshot_10.12.2024c.png)
