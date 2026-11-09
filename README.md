# Forest-fire-detection

Predicts how large an area a forest fire will spread, based on wind speed, temperature, and humidity (pandas, matplotlib, scikit-learn).
![AI101](https://img.shields.io/badge/AI101_Mini--Project-lightblue) ![Team](https://img.shields.io/badge/Team_46-lightblue) ![Python](https://img.shields.io/badge/Python_3.12+-lightblue)


## Team and roles

| Member | Entry no. | GitHub | Role |
| --- | --- | --- | --- |
| BLESS SINGH KUKREJA | 2026DAB1291 | [Bless-Kukreja](https://github.com/Bless-Kukreja) | Execution lead |
| NANABOLU BHAVISHYA REDDY | 2026MCB1548 | [Bhavishya-reddy275](https://github.com/Bhavishya-reddy275) | PPT lead |
| KESHAV MISHRA | 2026AIB1050 | [keshavmishra-dot](https://github.com/keshavmishra-dot) | Video lead |
| SAKSHAM PATHAK | 2025EEB1376 | [Saksham-Pathak](https://github.com/Saksham-Pathak) | Documentation lead |

All four members contributed code (see commit history).

## Project structure
 
```
Forest-fire-detection/
├── Datasets/
│   └── survey.csv         # 517 rows x 13 columns (UCI Forest Fires data)
├── src/
│   └── main.ipynb         # entry point: preprocessing, training, evaluation
├── requirements.txt       # pinned library versions
├── .gitignore
└── README.md
```
 
## Setup
 
Tested on Python [FILL: versions, e.g. 3.10 and 3.11] ([FILL: Windows / macOS / Ubuntu]).
 
```bash
git clone https://github.com/Bless-Kukreja/Forest-fire-detection.git
cd Forest-fire-detection
python -m venv venv
# Windows:   venv\Scripts\activate
# Linux/Mac: source venv/bin/activate
pip install -r requirements.txt
```
 
## How to run
 
1. `cd src`
2. `jupyter notebook main.ipynb`, then choose **Kernel -> Restart and Run All** (in VS Code: open `src/main.ipynb` and click **Run All**).
3. The notebook prints MAE, RMSE and R-squared on the test set and shows the plots.
4. Expected runtime: [FILL: e.g. under 1 minute].
Result: [FILL: test MAE, RMSE and R-squared, plus one sentence on what they mean].
 
## Expected output
 
![Notebook output](images/output.png)
 
[FILL: screenshot of the notebook's final results cells, saved as `images/output.png`]
 
## Links
 
Slides (5): [FILL: `slides.pdf` in this repo] · Video: [FILL: unlisted YouTube or Drive link]
 
## AI-use disclosure
 
- Claude: first draft of this README; edited and checked against the repo by Saksham.
- [FILL: each teammate adds the tools they used, what for, and how they checked the output]
- No AI was used to generate the dataset or the results.
 
