## An API for Neural Style Transfer
Image Stylizer is an image generator, made to artificially generate the
artistic version of your photo/image. You can choose your style and upload a photo
and let Image Stylizer paint it for you. This application is fully based on deep
learning, and implemented as a web service which follows the REST architecture.

The primary goal of our project is to provide the user with a stylized version of their
uploaded image. We do this by applying a Deep Learning method referred to as Neural
Style Transfer to the input image. 

Neural Style Transfer :
Style transfer is a process of migrating a style from one image (the Style-Image) to another
(the Content-Image). The goal is to synthesize a new image which is an artistic mixture of
content and style. At its core, this transfer task is not well-defined, and as such it could be
interpreted and addressed in various ways. Broadly speaking, the literature offers two
distinct approaches for handling the style transfer problem: The first is generalization of
classic texture synthesis methods. An alternative path towards handling style transfer
emerged recently, basing the transfer process on Convolutional Neural Networks (CNN).
The style transfer problem is addressed by returning to the classic texture synthesis route,
leaning on the vast knowledge accumulated in this field, while aiming to get visual results
that are on par with recently proposed methods. This method has been chosen as the
foundation for our algorithm due to its elegance, simplicity, and excellent results. The
results obtained with the proposed algorithm are competitive with the recent style transfer
algorithms, CNN or texture synthesis based. The created images are visually pleasing,
containing rich and diverse hallucinated parts brought from the style, while keeping the
essence of the content intact.

Architecture :
In HTTP there are five methods which are commonly used in a REST based
Architecture i.e., POST, GET, PUT, PATCH, and DELETE. These correspond to
create, read, update, and delete (or CRUD) operations respectively. For our project
we have used only POST & GET methods in building the API.
A Restful system consists of a:
● client who requests for the resources.
● server who has the resources.



