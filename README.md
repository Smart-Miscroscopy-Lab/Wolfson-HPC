# 🖥️ Wolfson-HPC Setup Guide

A step-by-step guide to get up and running on the Wolfson High Performance Computing (HPC) system.

---

## 1. 🔐 Log In to HPC

Log in through **ThinLinc** using your university credentials.

---

## 2. 🐍 Install Anaconda (if not already installed)

Download the Anaconda installer:

```bash
wget https://repo.anaconda.com/archive/Anaconda3-2022.05-Linux-x86_64.sh
```

---

## 3. 🐍 Activate Anaconda

Run the installer:

```bash
bash Anaconda3-2022.05-Linux-x86_64.sh
```

**This should now have Anaconda installed.**

---

## 4. Check with:

```bash
conda --version
```

---

## 5. Create a conda environemt:

```bash
conda create --name <yourenvname>
```
**Then activate your environment (do this everytime you want to log in)**
```bash
conda activate <yourenvname>
```

## 5. Install all the packages you want:

```bash
conda install torch matplotlib numpy pandas
```



