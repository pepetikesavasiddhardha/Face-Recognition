# Face-Recognition
# Here we will use Opencv library for actually creating the folders of images which we will use later for training
# The use of HAAR face classifier is to detect face and eyes in a frame and we will use this in our code
# Ultimately using above ideas we will create 4 folders of images each folder having around 100 images(by changing code we can create as many images as we want),each folder has images of particular person, i randomly named the 4 folders(persons) as dad,mom,pandu,siddu
# Now we will use transfer learning technique(we will use model which is already proven to be sucessful one) that is we will use VGG19 model which is trained on imagenet dataset
# We will use already trained model(i.e,model weights will not be trained based on this dataset), then we will flatten the layers
# Now we will fit training set to the vgg model and set certain epochs value in my case i took it 10
# Later we will capture the images of persons (test data) using webcam that is same way as we captured train dataset
# now using this trained model we will make predictions on the test dataset,we can expect good accuracy as Transfer learning models ingeneral give great accuracy 
