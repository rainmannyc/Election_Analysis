# **Election_Analysis**

## **Overview**

The purpose of the analysis was to audit election data from a Colorado election. The election commission has requested some additional data from our current audit. The main additional key elements were:

1. The voter turnout for each county
2. The percentage of votes from each county out of the total count
3. The county with the highest turnout

This means our assigment consisted of writing a code capable of collecting data from the election "csv." file and extracting the data onto a separate text file for the election commission to easily view. 

### **Election-Audit Result Analysis**

For the election, the total number of votes amounted to 369,711 votes. From the data sheet, we were able to extract data for each individual County. We can see in the list below, the County which received the highest number of votes and contributed to the highest percentage of votes was Denver, followed by Jefferson, and Arapahoe.

1. Denver: 82.8% (306,055)
2. Jefferson: 10.5% (38,855)
3. Arapahoe: 6.7% (24,801)

We were also able to view a data breakdown for each individual candidate. Showing the exact amount of votes each candidate received along with a percentage. In this case, Diana DeGette has received 73.8% of the votes enabling her to win the election followed by runner up, Charles Casper Stockham who received 23% of the votes. Unfortunately for Raymon Anthony Doane, he only received 3.1%, important data he may definitely want to consider if he'd like to run again. 

1. Diana DeGette: 73.8% (272,892)
2. Charles Casper Stockham: 23.0% (85,213)
3. Raymon Anthony Doane: 3.1% (11,606)
    
We can also see clearly from the data, Diana DeGette has received a substantial amount more votes than the runner up, 187,679 votes to be exact. We can also tell by the this information, that she received more amount of votes from Denver, than the other two County's combined. She blew away the competition with a staggering 272,892 winning the election with 73.8% of the votes.

* Winner: Diana DeGette
* Winning Vote Count: 272,892
* Winning Percentage: 73.8%

### **Conclusive Summary for the Commission**

In conclusion, the code can be repurposed for larger data sets for example if the election was nationwide. We can repurpose the code to edit and update data with even more states or candidates. We can do this by simply adding new lists or dictionaries to the script to collect more information from different categories.

![Image of ListDict](https://github.com/rainmannyc/election_analysis/blob/main/readme_images/ListandDictEdits.png)
  
We may also add more rows or columns to iterate pass as well if we'd like to add different information to the script, which can be done by tweaking or editing a few lines of code as shown below:

![Image of CollectProcess](https://github.com/rainmannyc/election_analysis/blob/main/readme_images/CollectProcessMore.png)

I also believe we should be able to output the data on different excel type files as well, converting the file and even possibly making a graph and chart to show data trends. 