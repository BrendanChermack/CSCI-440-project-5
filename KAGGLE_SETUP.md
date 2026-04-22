# Kaggle API Setup

## 1. Create a Kaggle account
Go to [kaggle.com](https://www.kaggle.com) and sign up if you don't have an account.

## 2. Download your API token
1. Click your profile picture (top right) and select **Settings**
2. Scroll to the **API** section
3. Click **Create New Token**
4. A file called `kaggle.json` will download automatically

## 3. Place the file in the right location
Open a terminal and run:

```bash
mkdir "$USERPROFILE/.kaggle"
```

Then move `kaggle.json` from your Downloads folder into `C:\Users\YOUR_NAME\.kaggle\`.

Your file should now be at:
```
C:\Users\YOUR_NAME\.kaggle\kaggle.json
```

## 4. Verify it worked
Run this in your terminal:

```bash
cat "$USERPROFILE/.kaggle/kaggle.json"
```

You should see:
```json
{"username":"your_username","key":"your_api_key"}
```

## 5. Run the notebook
Open `pneumonia_cnn.ipynb` and run the cells in order. The dataset will download automatically.
