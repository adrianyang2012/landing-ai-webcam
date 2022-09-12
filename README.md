# Intergrating-webcam-to-LandingLens

## Introduction
Let's learn what is LandingLens first.
LandingLens is a platform made by Landing AI which was founded by [Andrew Ng](https://www.andrewng.org/).
LandingLens is a thing that lets you make AI without programming or doing math.
Landing AI is also my [Dads](https://www.linkedin.com/in/kaiyangtw/) company.

![Screenshot 2022-09-11 8 17 39 PM](https://user-images.githubusercontent.com/69127002/189567699-e9256993-dab0-41bd-8e9c-b939298b7b5e.png)

## Control webcam in colab

I wrote this code on google colab that controlls to webcam and asks LandingLens for the result.
So you wont have to use any camera app.
You can take pictures for the training data and testing data.

![Screenshot 2022-09-11 9 50 43 PM](https://user-images.githubusercontent.com/69127002/189576244-145d4166-de20-43e9-b46d-00263c53689e.png)

## Upload to LandingLens and train models

Then I downloaded all of the data by clicking the files tab on the side and downloading them onto LandingLens

![Screenshot 2022-09-11 8 22 09 PM](https://user-images.githubusercontent.com/69127002/189568104-8c3dcc8e-a0bf-4715-a049-7dae96fcbc15.png)

### Labeling a few images

Start labeling by clicking on a image and go to the top left corner and click labbeling. Then you go to the select defect button and type create defect
Then, start making boxes.

![Screenshot 2022-09-11 9 55 06 PM](https://user-images.githubusercontent.com/69127002/189576989-de421114-96c5-4ff0-97b9-694d6c4899bf.png)

and then I pressed train!

![Screenshot 2022-09-11 8 36 12 PM](https://user-images.githubusercontent.com/69127002/189569366-c669b8ed-defa-48b2-ae70-481d402220f5.png)

## Test the model in LandingLens

I gathered a few more images and tested them to see how the model performed, It looks cool.

![Screenshot 2022-09-11 10 01 14 PM](https://user-images.githubusercontent.com/69127002/189577320-8cb66866-46ad-4a7a-91be-d16dc5af25b3.png)

## Intergrating the API in colab

Then I copied the curl command and a program that uses the LandingLens API to make the it predict stuff the same...  but with the webacam!

### How to use it yourself
Here is how you can use it yourself.
for now just press the first 2 cells and type training
and then you can take all the pictures
Then you load them onto LandingLens by clicking the file tab on the side!

![Screenshot 2022-09-11 8 37 08 PM](https://user-images.githubusercontent.com/69127002/189569467-f9069b28-339f-41a7-8101-c4635313db3b.png)

After that you label the pictures.
Then on the side click model and run live
After you do that
when it asks you for the api key and api secret part type your api key and secret from the LandingLens thing
to do that click on deploy and click on the icon on the top right corner
and click api key and press generate and then paste the api keys and api secrets onto your notebook
also paste the link from the curl command and do not use my link or else you are going to authencation error
Then you click the runtime button and click 

![screenshot](https://user-images.githubusercontent.com/69127002/189499541-83974ec7-9178-40be-8789-d36b9c981866.png)

Result:

![Screenshot 2022-09-11 8 34 09 PM](https://user-images.githubusercontent.com/69127002/189577666-832e996a-55f3-42d6-a805-b40f9c8aa5d2.png)
