# Analysis of Covid-19 Policy Effectiveness
A global analysis of the effectiveness of policy responses to COVID-19

Code implementation for the analysis and experiments used in the paper "A Global Analysis of the Effectiveness of Policy Responses to COVID-19" by Kwadwo Agyapon-Ntra and Patrick McSharry (PhD)

Preprint available [here](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4193848).

---
## Setup Instructions
For a clean run of the code, run `pip install -r requirements.txt` from the root of the folder in a fresh python virtual environment. The latest code was run with Python 3.10

The datasets used can be found below (you'll have to click on the Download button on each linked page) and were arranged in the same order seen below. (Links represent files, and non-links represent folders. Once downloaded, you may rename the files and refactor the `pd.read_csv` string arguments to your liking):  
* corruption
    * [corruption perception index](https://ourworldindata.org/grapher/ti-corruption-perception-index)
* education
    * [literacy rate by country](https://ourworldindata.org/literacy#global-literacy-today)
* freedom of expression
    * [freedom of expression](https://ourworldindata.org/grapher/freedom-of-expression?country=ARG~AUS~BWA~CHN)
* general
    * [owid covid data](https://ourworldindata.org/explorers/coronavirus-data-explorer)
* income relief
    * [debt relief](https://ourworldindata.org/grapher/debt-relief-covid)
    * [income support](https://ourworldindata.org/grapher/income-support-covid)
* mobility
    * [changes in visitors](https://ourworldindata.org/grapher/changes-visitors-covid)
* stringency
    * face coverings
        * [face covering policies](https://ourworldindata.org/covid-face-coverings)
    * gatherings and events
        * [public events](https://ourworldindata.org/grapher/public-events-covid)
        * [public gathering rules](https://ourworldindata.org/grapher/public-gathering-rules-covid)
    * information
        * [public information campaigns](https://ourworldindata.org/covid-public-information-campaigns)
    * lockdowns
        * [stay st home requirements](https://ourworldindata.org/covid-stay-home-restrictions)
    * movement restrictions
        * [internal movement](https://ourworldindata.org/grapher/internal-movement-covid)
        * [international travel](https://ourworldindata.org/grapher/international-travel-covid)
        * [public transport](https://ourworldindata.org/grapher/public-transport-covid)
    * school closure
        * [school closure measures](https://ourworldindata.org/grapher/school-closures-covid)
    * workplace closure
        * [workplace closure measures](https://ourworldindata.org/grapher/workplace-closures-covid)
    * [containment index](https://ourworldindata.org/grapher/covid-containment-and-health-index)
    * [stringency index](https://ourworldindata.org/covid-stringency-index)
<br/>
<br/>

Your folder structure should look something like this when you are done, depending on how you name your files (and refactor the code accordingly):  
![Screenshot of directory structure](https://user-images.githubusercontent.com/18174012/222743569-7279c99b-3028-4827-a8b1-d03539242da9.png)


    
