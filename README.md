# TF-IDF-with-ArchDaily
I learnd TF-IDF similarlity measure with web page named "Arch Daily"

## Motive
Recently I read about TF-IDF similarity measure. 
So I want to use it in real life, I applied "https://www.archdaily.com/" web page. The program finds other titles name similar to the title as user typing. Also, if there is a word user want to find, search an art piececs that contains that word. 

## Requirement
- Beautifulsoup
- pandas
- sklearn

## Python File
First, i have to gather arch daily data. While doing this project, gathering data i essentially study web crawling.
I also studied web crawling with googling. so code can so dirty and complex. Ask to be excused.

'Gather_ArchData' is code for gather data. This code collect each person's art piece title and descripment in arch daily.
<br>An example follows. https://www.archdaily.com/925586/enrico-fermi-school-bdr-bureau <br>
<img src = https://user-images.githubusercontent.com/55969260/65871434-5a014b80-e3b9-11e9-8015-e59f592fea89.png> <br>
// Collect title <br>
<img src =https://user-images.githubusercontent.com/55969260/65871924-689c3280-e3ba-11e9-9ea8-6d5ea2d75059.png> <br>
// Collect descriptions <br> <br>

similarity was analyzed using TF-IDF of the Scikit-learn library 'TfidfVecorizer' <br>
<img src = "https://user-images.githubusercontent.com/55969260/65872583-d563fc80-e3bb-11e9-9662-6531e2cc9d82.png"> <br>
Part of the code. <br>

## Data preview
<img src = https://user-images.githubusercontent.com/55969260/65872841-794da800-e3bc-11e9-9102-277c6a56696a.png> <br>
- Red underline : Page number
- Blue underline : Title
- Orange underline : Description
<br>

## Demo
1. Search similar page <br>
<img src = https://user-images.githubusercontent.com/55969260/65873637-8f5c6800-e3be-11e9-8beb-cc4b17c1b453.png> <br>
2. Search word <br>
<img src = https://user-images.githubusercontent.com/55969260/65873654-9a16fd00-e3be-11e9-892b-feabbc05baef.png> <br> 
