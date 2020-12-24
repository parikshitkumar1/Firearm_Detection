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
### Google Drive Link: https://drive.google.com/file/d/13ZwaPrg_OdhZKCPIhWHAAxDc1tNE4lSj/view?usp=sharing

## To run
```python
$ python3 detection.py
```
### Do change the path of the images you want to detect on by editing the main detection.py file, code to be edited will be in the images

### After downloading and adding weights, the directory should contain the following files:

![image](https://user-images.githubusercontent.com/52780573/102658162-084f0780-419d-11eb-8cf8-759934e049a9.png)

### Edit this code to change the path to the one with your images:

![image](https://user-images.githubusercontent.com/52780573/102658332-611ea000-419d-11eb-8e73-71376f0029d1.png)

## Result:

<img src="https://user-images.githubusercontent.com/52780573/101593570-26d33700-3a16-11eb-9776-0715fa156ad7.gif" data-canonical-src="" width="800" height="500" />

## Might Do
- [ ] Train with more data
- [ ] Implement with video
- [ ] Implement in real time
---
