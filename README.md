# similar_face_images
a silimar_face_images path from exist public dataset

. Table shows the current popular public and non-public face recognition datasets.
|Dataset|Identities|Images|Public|
|PubFig|200|58,000|yes|
|LFW|5,749|13,233|yes|
|WDRef|2,995|99,773|yes|
|CelebFaces|10,177|202,599|yes|
|CASIA-WebFace|10,575|494,414|yes|
|FaceBook|4,030|44M|No|
|Google|8M|200M|No|

Researchers in academia generally agree that the data used in research are more important than algorithms. 
At present, we do not have publicly available similar face datasets. 
Therefore, the first goal is to establish a similar Face Dataset.

This project provides similar face datasets generated using a multi-stage strategy for LFW and CASIA-WebFace.
In the NEW folder, the paths of similar facial datasets collected so far are stored. 
The first column in each txt file is the Euclidean distance between the two, and the second and third columns represent two pictures. 
Smaller Euclidean distance means higher similarity.
