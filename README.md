# ⚽ Hypothesis Testing with Men’s and Women’s Soccer Matches

## 📖 What is Hypothesis Testing?

**Hypothesis Testing** is a statistical method used to make decisions based on data. It helps determine whether an observed effect is **statistically significant** or just due to random chance.

In every test, we define:

- **H₀ (Null Hypothesis):** Assumes no effect or no difference.
- **H₁ (Alternative Hypothesis):** Assumes there is an effect or difference.

We then calculate a test statistic (like Z or T) and a **p-value** to decide whether to:

- ✅ **Reject H₀** → Evidence supports H₁  
- ❌ **Fail to reject H₀** → Not enough evidence to support H₁

This project analyzes historical soccer match data to test whether women's international matches result in more goals than men's, using hypothesis testing and statistical methods.

---

## 🧪 Tests Performed

| Test | Purpose |
|------|---------|
| **Shapiro-Wilk Test** | Check for normality in goal distributions |
| **Levene’s Test** | Test for equality of variances |
| **One-sample Z-Test** | Test if men's average goals > 2.5 |
| **Welch’s T-Test (Men vs Women)** | Compare mean goals between men and women |
| **Welch’s T-Test (FIFA vs Other)** | Compare goals in men's FIFA matches vs other tournaments |
| **Bootstrap (5000 resamples)** | Estimate standard error for t-tests |

---

## 🧰 Tech Stack

- **Language:** Python
- **Libraries:**  
  - `pandas`, `numpy`  
  - `matplotlib`, `seaborn`  
  - `scipy`, `pingouin`  

---

## 👩‍💻 Author

**Shalini Dey**  
Exploring Data Through Python & Statistical Thinking🌟
