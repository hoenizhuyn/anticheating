#  Cheating detection with Machine Learning

[Project proposal](https://docs.google.com/document/d/1PUzJkcLDxFbYRR6oJ0ql6Cc-tG1CB0NS91TuwV8VU8c/edit?tab=t.0)  

- Utilized DaisyKit for pose estimation and keypoint extraction. 
- Pose landmarks are standardized with Numpy and stored in Pandas Dataframe. 
- Embbed keypoints data and Implemented classification using Tensorflow tensors and Keras neural network respectively, trained on Ubuntu WSL.
---


##  Technologies Used

- [Daisykit](https://daisykit.nrl.ai/)
- Python under 3.10

---

##  Getting Started

### 1. Clone the Repo

```bash
git https://github.com/hoenizhuyn/anticheating.git
cd  anticheating
```
### 2. Install Dependencies

```bash
pip install -r requirements.txt
```
Make sure you have daisykit installed:

```bash
pip install daisykit
```
### 3. Training
Since Tensorflowjs is only compatible with Linux, training process needs to take place in Ubuntu- Window subsystem for Linux
## Project goals
- Discourage cheating behaviour
- Lightweight, can run on CPU
