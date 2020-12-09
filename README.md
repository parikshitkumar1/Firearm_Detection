---
# Firearm Detection

## Motivation
To be used in real-time for security systems
## Requirements
Python 3.8 or above with all [requirements](requirements.txt) dependencies installed. To install run:
```python
$ pip3 install -r requirements.txt
```
### Downloads weights from here and put them in the root of this directory: 
### https://drive.google.com/file/d/1nITfy2NLJDMwfkEkPvadbUBs8zYs8yUL/view?usp=sharing

## To run
```python
$ python3 detection.py
```
### Do change the path of the images you want to detect on by editing the main detection.py file, code to be edited will be in the images

### After downloading and adding weights, the directory should contain the following files:

![Screenshot from 2020-12-09 11-06-52](https://user-images.githubusercontent.com/52780573/101591249-16b95880-3a12-11eb-98b6-523326025403.png)

### Edit this code to change the path to the one with your images:

![Screenshot from 2020-12-09 10-46-09](https://user-images.githubusercontent.com/52780573/101591311-46686080-3a12-11eb-8288-655c9b759f51.png)

## Result:

![simplescreenrecorder-2020-12-09_10 25 37(4)](https://user-images.githubusercontent.com/52780573/101593570-26d33700-3a16-11eb-9776-0715fa156ad7.gif)

![simplescreenrecorder-2020-12-09_10 25 37](https://user-images.githubusercontent.com/52780573/101593384-d360e900-3a15-11eb-8107-ea885ae4adb1.gif)

## Might Do
- [ ] Implement in real time, train with more data
----
