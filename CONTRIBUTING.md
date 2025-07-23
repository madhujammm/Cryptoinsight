# ✨ Contributing to CryptoInsight

Welcome! 👋  
**CryptoInsight** is an open-source, beginner-friendly crypto dashboard that lets users monitor real-time cryptocurrency prices, analyze market trends, and track wallet balances using blockchain APIs.

Built with Python and Streamlit, our goal is to simplify the crypto experience through clean visualizations and a user-first design.

Whether you're a crypto enthusiast, data lover, or developer — we’d love your help in making this project even better! 🚀

---

## 🧰 Tech Stack

- **Backend / Dashboard:** Python, Streamlit
- **Data & Analytics:** Pandas, NumPy
- **Visualization:** Matplotlib, Plotly
- **API:** CoinGecko API
- **Version Control:** Git & GitHub

---

## 🛠️ Getting Started Locally

### 1. Fork the Repo

Click the **Fork** button in the top right of this GitHub repo. Then clone your fork:

```bash
git clone https://github.com/YOUR-USERNAME/CryptoInsight.git
cd CryptoInsight
````

### 2. Set Up a Virtual Environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit App

```bash
streamlit run app.py
```

The dashboard should open in your browser at [http://localhost:8501](http://localhost:8501) 🎉

---

## 📂 Project Structure

```
CryptoInsight/
├── app.py                  # Main Streamlit dashboard
├── requirements.txt        # Python dependencies
├── data/                   # (Optional) Local CSVs or cache
├── utils/                  # Helper functions (API calls, plotting, etc.)
└── README.md
```

---

## 🔧 Code Style Guide

* Follow [PEP8](https://peps.python.org/pep-0008/) for Python formatting.
* Use docstrings and meaningful variable names.
* Keep functions modular and reusable.
* Comment wherever logic isn't obvious.
* Stick to lowercase\_underscore for function/variable names.

---

## 🚀 Submitting a Contribution

### 1. Create a New Branch

```bash
git checkout -b feature/your-feature-name
```

### 2. Make Your Changes

Add features, fix bugs, improve UI, etc. Test your changes thoroughly.

### 3. Stage and Commit

```bash
git add .
git commit -m "feat: add [your-feature-name] to dashboard"
```

### 4. Push and Open a PR

```bash
git push origin feature/your-feature-name
```

Then go to your forked repo and click **“Compare & Pull Request”**. In the PR description:

* Clearly describe your changes
* Mention any related issues (e.g. `Closes #5`)
* Add screenshots if applicable

---

## 🧪 Ideas You Can Work On

* [ ] Dark mode toggle
* [ ] Real-time wallet tracker (via address)
* [ ] More interactive charts (e.g. candlesticks)
* [ ] Historical performance comparison
* [ ] News feed integration (CryptoPanic API?)

---

## 💬 Need Help?

Feel free to open an issue or drop a discussion — we’re here to help!

---

## 🙌 Thanks for Contributing!

CryptoInsight is only possible thanks to awesome folks like you.
Let’s make crypto more transparent, fun, and user-friendly — together. 🌍💸
