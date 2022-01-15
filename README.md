# AI-shark-GAN-coursework #

## Google Colab link ##
https://colab.research.google.com/drive/1HOetYBVbnGFkplcQNtkK5pK1-o7Wf4oz?usp=sharing


## Fish dataset created using the following sources (sizes too large for github but contain 1.4k images) ##

* Cutter, G.; Stierhoff, K.; Zeng, J. (2015) "Automated detection of rockfish in unconstrained underwater videos using Haar cascades and a new image dataset: labeled fishes in the wild," IEEE Winter Conference on Applications of Computer Vision Workshops, pp. 57-62. https://swfscdata.nmfs.noaa.gov/labeled-fishes-in-the-wild/ 

* Joly A., Goeau H., Glotin H., Spampinato C., Bonnet P., Vellinga W.-P., Planquè R., Rauber A., Palazzo S., Fisher R., and others}, LifeCLEF 2015: multimedia life species identification challenges, International Conference of the Cross-Language Evaluation Forum for European Languages, pp. 462-483, Springer, 2015. http://www.perceivelab.com/datasets 

* Zhuang, P. Wang, Y. Qiao, Y. 2018. WildFish: A Large Benchmark for Fish Recognition in the Wild. 2018 ACM Multimedia Conference pp. 1301-1309. https://github.com/PeiqinZhuang/WildFish 


## Shark datasets were created by using "Image Downloader Continued" on the following websites: ##
* Google images
* Flickr
* Pinterest
* Voxel51

These were augmented with a pre-collected dataset found on Kaggle containing shark species:
* Lautaro. 2020. Shark Species collection of shark images classified by 14 different species. https://www.kaggle.com/larusso94/shark-species 


## Shark Dataset and Model Google Drive Link ##

The zip file contains the following:

* CNN_fake_dataset_sharks - the final combined dataset containing 4 different shark species and an augmented Oceanic Whitetip dataset

* network-snapshot-000520.pkl - a pkl file of the trained model taken at 520 kimgs, this was used to generated the images below
* whitetips_520kimg - a collection of 300 randomly generated Oceanic Whitetip images using my StyleGAN2 trained model at 520kimgs

* oceanic_whitetips-real - the initial Oceanic Whitetip dataset before reinforcement (there are fair few images with text, but removing them limited the dataset far too much)
* oceanic_whitetips-real+fake - the combined real and fake Oceanic Whitetip dataset for comparison with the above
