# Sickle-RBC-data
Sickle RBC dataset 
# A deep convolutional neural network for classification of red blood cells in sickle cell anemia

Abstract: 
Sickle cell disease (SCD) is a hematological disorder leading to blood vessel occlusion accompanied by painful episodes and even death. Red blood cells (RBCs) of SCD patients
have diverse shapes that reveal important biomechanical and bio-rheological characteristics, e.g. their density, fragility, adhesive properties, etc. Hence, having an objective and
effective way of RBC shape quantification and classification will lead to better insights and eventual better prognosis of the disease. To this end, we have developed an automated,
high-throughput, ex-vivo RBC shape classification framework that consists of three stages.First, we present an automatic hierarchical RBC extraction method to detect the RBC region
(ROI) from the background, and then separate touching RBCs in the ROI images by applying an improved random walk method based on automatic seed generation. Second, we
apply a mask-based RBC patch-size normalization method to normalize the variant size of segmented single RBC patches into uniform size. Third, we employ deep convolutional neural
networks (CNNs) to realize RBC classification; the alternating convolution and pooling operations can deal with non-linear and complex patterns. Furthermore, we investigate the
specific shape factor quantification for the classified RBC image data in order to develop a general multiscale shape analysis. We perform several experiments on raw microscopy
image datasets from 8 SCD patients (over 7,000 single RBC images) through a 5-fold cross validation method both for oxygenated and deoxygenated RBCs. We demonstrate that the
proposed framework can successfully classify sickle shape RBCs in an automated manner with high accuracy, and we also provide the corresponding shape factor analysis, which can
be used synergistically with the CNN analysis for more robust predictions. Moreover, the trained deep CNN exhibits good performance even for a deoxygenated dataset and distinguishes
the subtle differences in texture alteration inside the oxygenated and deoxygenated RBCs.

For more details, please refer to the following: 

http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005746)

  
## Citation

	@article{xu2017deep,
  	title={A deep convolutional neural network for classification of red blood cells in sickle cell anemia},
  	author={Xu, Mengjia and Papageorgiou, Dimitrios P and Abidi, Sabia Z and Dao, Ming and Zhao, Hong and Karniadakis, George Em},
  	journal={PLoS Computational Biology},
  	volume={13},
  	number={10},
  	pages={e1005746},
  	year={2017},
  	publisher={Public Library of Science}
	}

##
