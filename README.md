# 🎬 IMDb Top Movies Web Scraping

A Python project that scrapes IMDb’s **Top Movies** list and organizes the data into a clean, structured dataset with titles, ratings, posters, and direct IMDb links.  
The project is implemented in **Jupyter Notebook** using `requests`, `BeautifulSoup`, and `pandas`.

---

## 🚀 Features
- ✅ Extracts **Movie Title, IMDb Rating, Poster, and IMDb Link**  
- ✅ Displays results in a **well-formatted Pandas DataFrame**  
- ✅ Option to **save dataset as CSV** for future analysis  
- ✅ Poster images can be displayed inside Jupyter or downloaded locally   

Key features include:
- Sending HTTP requests to fetch webpage content  
- Parsing HTML data using **BeautifulSoup**  
- Extracting specific information (e.g., text, links, tables, attributes)  
- Organizing scraped data into **CSV/Excel/DataFrames**  
- Optional preprocessing and visualization of results  

---

## 🚀 Setup Instructions

1. Install dependencies:
   ```bash
   pip install -r requirements.txt

---

## 🛠️ Tech Stack
- **Python 3**  
- **Libraries**:  
  - `requests` → fetch webpage  
  - `beautifulsoup4` → parse HTML / JSON  
  - `pandas` → structure and analyze data  
  - `IPython.display` → render images inside notebook

---

## 📌 Key Learnings
- Handling request headers to avoid HTTP 403 errors  
- Extracting structured **JSON-LD** data instead of only HTML tags  
- Working with Python for real-world web scraping tasks  

---

## 📊 Example Output (Jupyter Notebook)
| 🎬 Title | ⭐ Rating | 🖼️ Poster | 🔗 IMDb Link |
|----------|----------|-----------|--------------|
| The Shawshank Redemption | 9.2 | ![](https://m.media-amazon.com/images/M/MV5BMDFkYTc0MGEtZmRhMC00ZDJlLWFmNTEtODM1ZDIzZjNjZWRiXkEyXkFqcGdeQXVyNDYyMDk5MTU@._V1_UY98_CR0,0,67,98_AL_.jpg) | [Link](https://www.imdb.com/title/tt0111161/) |
| The Godfather | 9.2 | ![](https://m.media-amazon.com/images/M/MV5BM2MyNjYxNmYtYTAwMC00ZjQ5LWFmNTEtODM1ZDIzZjNjZWRiXkEyXkFqcGdeQXVyNzkwMjQ5NzM@._V1_UY98_CR1,0,67,98_AL_.jpg) | [Link](https://www.imdb.com/title/tt0068646/) |

