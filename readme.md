# Bank Statement Converter 📄

![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![GitHub](https://img.shields.io/github/license/tosinshada/bank-statement-converter?color=%232F3741&style=for-the-badge)

This is a simple bank statement converter that converts Nigerian bank statements from PDF to a structured format. 
It uses Python and Jupyter Notebook to extract data from the PDF file and convert it to CSV format.

## 💻 Tech Stack

**Language** - [Python](https://www.python.org/)  
**Notebook** - [Jupyter](https://jupyter.org/)  
**PDF Extraction** - [Camelot](https://camelot-py.readthedocs.io/en/master/)  
**Data Cleaning** - [Panda](https://pandas.pydata.org/)

## 👨🏻‍💻 Running Locally

You can start using this project locally by running the following command in your desired directory:

```bash
# uv
uv sync
```

Then add the bank statement pdf file you want to convert to the `docs` directory in the project's root directory. 
After that, you should reference the file in the Jupyter Notebook file `<bank>-extract.ipynb` and run it to convert the PDF file to CSV format.

## 📂 Bank Status
| Bank Name | Status |
| --------- | ----- |
| [Access Bank](https://www.accessbankplc.com/) | ✅ |
| [First Bank](https://www.firstbanknigeria.com/) | ✅ |
| [Opay](https://www.opayweb.com/) | ✅ |
| [GT Bank](https://www.gtbank.com/) | ❌ |
| [Zenith Bank](https://www.zenithbank.com/) | ❌ |
| [Union Bank](https://www.unionbankng.com/) | ❌ |
| [UBA](https://www.ubagroup.com/) | ❌ |
| [Wema Bank](https://www.wemabank.com/) | ❌ |
| [Fidelity Bank](https://www.fidelitybank.ng/) | ❌ |
| [Stanbic IBTC](https://www.stanbicibtcbank.com/) | ❌ |
| [Ecobank](https://www.ecobank.com/) | ❌ |
| [Standard Chartered Bank](https://www.sc.com/ng/) | ❌ |
| [Sterling Bank](https://www.sterling.ng/) | ❌ |
| [Providus Bank](https://www.providusbank.com/) | ❌ |
| [Moniepoint](https://www.moniepoint.com/) | ❌ |

## 📥 Contributing

Contributions are welcome! If you want to contribute to this project, please note the following:
- do not add any sensitive information to the codebase e.g. the bank statement pdf file. 
- The content of the docs folder are ignored by git, so you can add your bank statement pdf files there.
- If you want to add a new bank, please create a new Jupyter Notebook file with the name `<bank>-extract.ipynb` and add it to the `notebooks` folder.
- Make sure to clear your notebook output before committing your changes to prevent sensitive information from being committed.

## ✨ Feedback & Suggestions

If you have any suggestions/feedback, you can contact me by [email](mailto:tosin@thezentra.com). 
Alternatively, feel free to open an issue if you find bugs or want to request new features.

## 📜 License

Licensed under the MIT License, Copyright © 2025

---

Made with 🤍 by [Tosin Shada](https://github.com/tosinshada) 👨🏻‍💻 and [contributors](https://github.com/tosinshada/bank-statement-converter/graphs/contributors).