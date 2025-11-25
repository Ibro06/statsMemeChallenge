# Selection Bias & Missing Data Challenge - Part 2

**Statistics Meme: Visualizing Selection Bias**

This repository contains my submission for the Selection Bias & Missing Data Challenge - Part 2, demonstrating the concept of selection bias through a four-panel visual meme. The project uses Python and Quarto to create an educational visualization that helps explain how systematic missing data patterns can distort statistical estimates.

## 🌐 Website

**View the live website:** [https://ibro06.github.io/statsMemeChallenge/](https://ibro06.github.io/statsMemeChallenge/)

## 📊 About This Project

This project creates a statistics meme that visually demonstrates selection bias, a critical concept in data analysis and statistics. The meme shows four panels:

1. **Reality** - The original photograph (truth)
2. **Your Model** - A stippled representation (sampled data)
3. **Selection Bias** - A bold letter "S" (systematic missing data pattern)
4. **Estimate** - The stippled image with "S" mask applied (biased estimate)

## 🎯 Key Concepts

Selection bias occurs when the data we observe isn't representative of the population we're trying to understand. This visualization helps demonstrate:

- How systematic missing data patterns can distort our understanding
- Why random sampling isn't always sufficient
- The importance of asking: **"Does my sample match my population of interest?"**

## 📁 Repository Contents

- `index.qmd` - Quarto document with code to generate the meme
- `40FCF51B-3864-4005-86C0-19561AC53EAD_1_105_c.jpeg` - Original image used for the meme
- `statistics_meme.png` - Generated four-panel statistics meme
- `index.html` - Rendered HTML output (auto-generated)

## 🛠️ Technology

- **Python** - Image processing and meme generation
- **Quarto** - Document rendering
- **Libraries**: NumPy, PIL/Pillow, Matplotlib, SciPy

## 📝 How It Works

The code implements the following process:
1. Loads the original image and converts it to grayscale
2. Generates a stippled version using weighted random sampling (darker areas have higher probability of dots)
3. Creates a bold "S" mask matching the image dimensions using PIL/Pillow
4. Applies the "S" mask to the stippled image to create a biased estimate (removes dots in the "S" shape)
5. Assembles all four panels into a single meme image with pink headers and white backgrounds

The visualization demonstrates that when selection bias is present, missing data follows a systematic pattern (the "S") rather than being random, leading to distorted estimates.

## 🔗 Related Resources

- Original Challenge: [flyaflya.github.io/statsMemeChallenge](https://flyaflya.github.io/statsMemeChallenge)
- Source Repository: [github.com/flyaflya/statsMemeChallenge](https://github.com/flyaflya/statsMemeChallenge)

## 📄 License

See the [LICENSE](LICENSE) file for details.
