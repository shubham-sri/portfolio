# Data Science Portfolio

---

## Image Processing

### Finding Lane Lines

The goal of this first project was to create a **simple pipeline** to detect road lines in a frame taken from a **roof-mounted camera**.

**Basic idea and thinking**
I have a question before staring this project. How human can recognize lane stips on the road? So I proccessed data which is in my mind and come with few points

- Houman are good to recognize colors even very small change in color can be recognized by human and I used this thought as base to build this project
- I have to split intrest area into two part which contain one strip of lane, which help in left, right identification and disconnections.

**Pipeline desciption**
- Color Mask
- Smoothing
- Gaussian Blur
- Canny Edge Detection
- Region of Interest
- Hough Lines
- Weighted Image


[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/shubham-sri/self-driving-car/tree/main/lane_finding)
