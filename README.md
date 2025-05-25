# GNN-SRGAN

### Generative Neural Networks – Final Project

This project explores two deep learning-based models for image super-resolution:

- **SRGAN** (Super-Resolution Generative Adversarial Network)  
- **ESRGAN** (Enhanced SRGAN)

---

## 🔧 Models

- **Baseline Model:** `SRGAN.ipynb`  
- **Enhanced Model:** `Enhanced_SRGAN.ipynb`

---

## 📂 Dataset

This project uses the [DIV2K dataset](https://data.vision.ee.ethz.ch/cvl/DIV2K/) for training and validation.

### Dataset Directory Structure:

content/
│── data/
│   ├── data/
│   │  ├── DIV2K_train_HR/ (training set)
│   │  ├── DIV2K_valid_HR/ (validation set)

> 📌 **Note:** Place your dataset inside the `content/` directory before running the training notebooks.

---

## 🚀 Usage

### 📊 Benchmark Testing

To evaluate the models using a standard test set, organize your benchmark data as follows:



content/
│── data/
│   ├── test/
│   ├   ├─ DataSet
│   ├   ├  ├─ Set4
│   │   │  ├── data/ (LR images)
│   │   │  ├── target/ (HR images)

### Benchmark Notebooks:

- `SRGAN_benchmark.ipynb`
- `ESRGAN_benchmark.ipynb`

These notebooks demonstrate example evaluation results on the benchmark dataset.

---

## 📈 Example Results

Example output images and PSNR/SSIM scores are provided in the benchmark notebooks for comparison.

---

## 📝 License

This project is for academic purposes only.

