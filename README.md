# TODO

- save scan segmentations together with pixel_spacing and origin 0 in .npz files?
- look at the nodules we cannot detect
- ordering of slices for kaggle data (Jonas)


ssh -X -p 10001 ikorshun@localhost
scp -P 10001 /mnt/sda3/data/kaggle-lung/stage1_sample_submission.csv  ikorshun@localhost://mnt/storage/data/dsb3/

## biggest nodule
1.3.6.1.4.1.14519.5.2.1.6279.6001.287966244644280690737019247886 (32 mm)

## smallest nodule
1.3.6.1.4.1.14519.5.2.1.6279.6001.151764021165118974848436095034 (3 mm)

## LUNA mm_shapes (z,y,x):

min z: (u'1.3.6.1.4.1.14519.5.2.1.6279.6001.952265563663939823135367733681', array([ 165.5,  254. ,  254. ]))      ]))
max z: (u'1.3.6.1.4.1.14519.5.2.1.6279.6001.223098610241551815995595311693', array([ 416.,  370.,  370.]))
min yx: (u'1.3.6.1.4.1.14519.5.2.1.6279.6001.300270516469599170290456821227', array([ 263.19999552,  236.        ,  236.        ]))
max yx: (u'1.3.6.1.4.1.14519.5.2.1.6279.6001.202811684116768680758082619196', array([ 332.5       ,  499.99975586,  499.99975586]))
(u'1.3.6.1.4.1.14519.5.2.1.6279.6001.174168737938619557573021395302', array([ 292.5       ,  499.99975586,  499.99975586]))
(u'1.3.6.1.4.1.14519.5.2.1.6279.6001.234400932423244218697302970157', array([ 357.5       ,  499.99975586,  499.99975586]))
(u'1.3.6.1.4.1.14519.5.2.1.6279.6001.803808126682275425758092691689', array([ 311.25      ,  493.00018311,  493.00018311]))
(u'1.3.6.1.4.1.14519.5.2.1.6279.6001.250863365157630276148828903732', array([ 371.25      ,  486.00012207,  486.00012207]))


## NEED TO CHECK
LUNA, strange image border: 1-1.3.6.1.4.1.14519.5.2.1.6279.6001.249530219848512542668813996730 
LUNA 0-1.3.6.1.4.1.14519.5.2.1.6279.6001.233001470265230594739708503198