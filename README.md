
# MWCD (Multi Weather Conditions Dataset for Autonomous Driving)

This repository contains a comprehensive dataset of **5,765 high-resolution images (1920x1080)** with meticulously annotated **2D bounding boxes**, designed for object detection in autonomous driving systems under various weather conditions.

## Dataset Overview

- **Total Images**: 5,765
- **Image Resolution**: 1920x1080
- **Annotations**: 2D bounding boxes
- **Object Classes**:
  - Person
  - Bicycle
  - Car
  - Motorcycle
  - Bus
  - Truck
  - Traffic Light

## Weather Conditions Covered
- Day
- Night
- Rain
- Fog
- Snow
- Sand

## Geographic Diversity
The dataset includes images collected from diverse locations to ensure a wide range of object instances:
- **Tehran, Iran**
- **The Netherlands** (focus on bicycles)
- **Ho Chi Minh City, Vietnam** (focus on motorcycles)

## Example Images

Below are some example images from the MWCD dataset for autonomous driving:

![Day Example](MWCD/Day13-109.jpg)  
*Daytime Image Example*

![Night Example](MWCD/N0-017.jpg)  
*Nighttime Image Example*

![Rain Example](MWCD/R12-014.jpg)  
*Rainy Weather Image Example*

![Snow Example](MWCD/Sn3-769.jpg)  
*Snowy Weather Image Example*

## Dataset Structure

```
/MWCD
  /images
    /train
    /val
  /annotations
    /train
    /val
```

## Download the Dataset

You can download the full MWCD dataset from the following link:  
[Download MWCD Dataset](https://drive.google.com/file/d/1-s-A5AObOYwLG3P98TdcArUpouXK_O1X/view?usp=sharing)

## Usage Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/ehsanDL/MWCD.git
   ```
2. The dataset can be used with popular object detection frameworks like YOLO. Ensure the annotations are in the correct format.

## License

This dataset is licensed under the MIT License. You are free to use, modify, and distribute this dataset in your own projects, provided that you include the following copyright notice:

```
MIT License

Copyright (c) [Year] [Your Name or Organization]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

