# UNet_BKAI_NeoPolyp_Segmentation
- Please don't change the files layout in this repo
- Replace the placeholder model with the real model in the link below:<br>
  https://drive.google.com/file/d/1Fel9Xi54aLhWFiF_YWm91HGemGZST58O/view?usp=sharing <br>
  Replace_this_file_with the_real_model.pth -> PolypModel.pth
- Installation before run:<br>
   pip install segmentation-models-pytorch<br>
   pip install albumentations
- Commands:
    git clone https://github.com/DoDoanHoangDu/UNet_BKAI_NeoPolyp_Segmentation
    cd UNet_BKAI_NeoPolyp_Segmentation
    python infer.py --image_path image.jpeg
