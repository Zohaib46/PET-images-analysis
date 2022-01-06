Co-registration with AFNI

Co-registration means to bring two objects into the same space so that each location within one object corresponds to the same location in the other. Here one image is anatomical we can call it our standard template, second image we take from data to superimpose on template. In AFNI we use tool call “Nudge Dataset” for co-registration of images. We can rotate two volumes in any possible way to arrange them good manner by using this tool.
In AFNI we see images in three windows called Axial, sagittal and coronal respectively. 

![first](https://user-images.githubusercontent.com/97203740/148406796-1d4d9a61-7828-4d98-ae4d-508a591c967f.jpg) ![second](https://user-images.githubusercontent.com/97203740/148406812-d9cc39ba-a004-4f49-b231-59933bed8475.jpg) ![third](https://user-images.githubusercontent.com/97203740/148406830-c1dea405-ec91-4703-8a4a-3c9a8ca0b1c0.jpg)

When we register our data images on this template, we actually apply some operation like rotation and translation by using nudge dataset.
This shows the screen of nudge dataset which we use for moving our data images to fix with template. 
![fifth](https://user-images.githubusercontent.com/97203740/148408104-d48c4081-b02b-4c73-8263-5144bda77a2a.jpg)
![sixth](https://user-images.githubusercontent.com/97203740/148408116-a5c5f5ba-ee7d-4e80-ae77-5c84dcf45d2a.jpg)
![forth](https://user-images.githubusercontent.com/97203740/148408081-097b19db-047b-43c7-b31a-f59b3220c523.jpg)

Here nudge dataset includes a lot of options to operate on images data like angels, shifts up/down, right, left, and so on. These options are applied on axial, sagittal and coronal to make best fit of data on template. After applied this operation we get our results looks like this
Usually it looks like in above images our data is fit well with the template but technically it is not well. After processing the result of this co-registation we get some noise which reflects our co-registration is not good. To make this better we repeat our process of co-registation until we get our good results as we want (stroke or other). That’s why co-registration is time consuming process, because we have to do this process with naked eye.
The common obervation is seen that we have different age,size and weight animals. This makes a big difference in co-registration. Due to different size of animal matching with template is not same for every animal. Another important factor is after making stroke or injury in the brain then we scan brain for next 3 week then in this period the brain size incresese as compared to first week brain size. So these are possible observation that make co-registration a difficult and time consuming process.


   ![a1](https://user-images.githubusercontent.com/97203740/148408321-60c6c04d-e59e-4b7a-a37e-924277e58e78.jpg) ![a2](https://user-images.githubusercontent.com/97203740/148408341-564dacf1-f25c-497a-a3fa-f4557f580d1b.jpg)
