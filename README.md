<p align="center">
  <a href="https://www.perceptilabs.com">
  <img src="./pl_logo.png">
  </a>
</p>

# Fabric Stain Defect Classification in Textile Quality Control

This dataset<sup>1</sup> contains images depicting *normal* and *stained* fabrics for defect classification in textile quality control.

The data can be used to build and train an ML model that uses image recognition to classify whether or not a picture of a textile depicts stain defects.

# Structure

This repo contains the following structure:

- **data/images**: contains **defect_free** and **stain** sub directories, each containing their respective images.  
- **dataset.csv**: CSV file that maps classification labels to images.

<p align="center">
  <img src="./sample.png">
</p>

The following shows a partial example of the data stored in **dataset.csv**:

| **labels**  | **images**                    |
|-------------|-------------------------------|
| stain       | data/images/stain/1.jpg       |
| stain       | data/images/stain/2.jpg       |
| defect_free | data/images/defect_free/1.jpg |
| defect_free | data/images/defect_free/2.jpg |

The labels used in the CSV are:

- **stain**: stained textile is depicted in the image
- **defect_free**: non-stained textile depicted in the image

# Community

Got questions, feedback, or want to join a community of machine learning practitioners working with exciting tools and projects? Check out our [Community](https://forum.perceptilabs.com/)!

<sup>1</sup> Dataset Credits: https://www.kaggle.com/priemshpathirana/fabric-stain-dataset

