# Real-Estate-Predictor-Singapore
# Develop a Deep Learning–based property value prediction model using tabular data 
%% [markdown]
# # ITI123 Milestone Project: Real Estate Price Prediction (DNN)
#
# **Student Name:** FONG Siang Yi
# **Student ID:** 8440104B
#
# ## 1. Setup and Initialization
# Importing necessary libraries for data manipulation, preprocessing, and deep learning.

# %%
…from tensorflow.keras.models import Model
from tensorflow.keras.layers import Input, Dense, Dropout, BatchNormalization, Concatenate, Embedding, Flatten
from tensorflow.keras.callbacks import EarlyStopping, ReduceLROnPlateau
from tensorflow.keras.optimizers import Adam

# Set random seed for reproducibility
np.random.seed(42)
tf.random.set_seed(42)

print(f"TensorFlow Version: {tf.__version__}")
