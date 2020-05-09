# AnimeGAN

Based on https://github.com/TachibanaYoshino/AnimeGAN

## Requirements  
- python 3.7 or higher
- numpy  
- tensorflow 1.15.2  
- opencv  
- tqdm  
- glob  
- argparse  

## Usage 

#### Generation based on pretrained model with Hayao Miyazaki 宮崎 駿 style 

1. Download pretrained model, for example: 

    * [Original with code](https://github.com/TachibanaYoshino/AnimeGAN/releases/tag/Haoyao-style_V1.0)
    * [Mirror (checkpoints only)](https://cloud.mail.ru/public/2Nv9/2C8wXNDLz)

2. Put checkpoints files into main_project_folder/checkpoint
3. Put new images into dataset/test/real
4. Don't forget to install requirements and then execute:

```python
python test.py --checkpoint_dir checkpoint/ --test_dir dataset/test/real --style_name H
```

____  
## Results  

### Before
![](https://github.com/Nejel/AnimeGAN/blob/master/doc/shotakot_before.jpg) 

### After
![](https://github.com/Nejel/AnimeGAN/blob/master/doc/shotakot_after.jpg)  
 