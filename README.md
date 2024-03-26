# aws-text-speech-convertion
In this, project we are going to convert any text file to sppech by using amazon polly service and s3 :
in the amazon console ,enter amazon poly and click on try poly then enter the input as a text and choose different languages and different accents in th options
![Screenshot 2024-03-26 164942](https://github.com/srimanth496/aws-text-speech-convertion/assets/84217751/49d42479-02c1-4dd3-8c48-ef70b19307b1)

in the options enable ssml ,by doing that we can able to modify the speech output voice , for instance add time delay between the words .
![Screenshot 2024-03-26 171126](https://github.com/srimanth496/aws-text-speech-convertion/assets/84217751/b148a7bb-4703-4664-8485-78ea99a31ae6)


use lambda function to trigger the event when ever upload any audiuo file that is converted from amazon poly

![Screenshot 2024-03-26 171847](https://github.com/srimanth496/aws-text-speech-convertion/assets/84217751/dc1339cd-a7f7-4b8c-be5b-e88bc29b41f2)

add trigger and named as text-speech

![image](https://github.com/srimanth496/aws-text-speech-convertion/assets/84217751/e68b761e-3f60-4fe7-bee2-19f641620e24)

