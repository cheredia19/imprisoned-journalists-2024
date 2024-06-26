# Don’t forget them: more than 700 journalists and media workers remain imprisoned
-	16,25% were detained in China
-	At least a third of the imprisoned media workers were charged with anti-state crimes
-	Freelancers are particularly at risk, say CPJ and RSF figures
	
_By César Heredia, data journalist_

At least **seven hundred twenty journalists and media workers from 59 countries are currently imprisoned or disappeared** (including forced disappearances), according to data from the Committee to Protect Journalists (CPJ) and Reporters Without Borders (RSF for its French acronym).

China (117), Myanmar (75), Belarus (43), and Russia (42) are the States with more journalists detained as of today. However, based on their respective populations, Bahrain (6.73), Eritrea (5.87), and Belarus (4.53) have more journalists imprisoned per million inhabitants.

## Imprisoned journalists per country

<FlatUiTable
  data={{
    url: 'per_million.csv'
  }}
/>

### Freelancers are particularly vulnerable

22.6% (163) of the imprisoned or disappeared journalists **are not formally enlisted in any organization or media outlet**. As a consequence, they were labeled as **freelancers** by CPJ and RSF. Of those, 12.9% (21) were detained in Myanmar, 11.7% (19) in Iran, and 11% (18) in Syria. 

## Imprisoned freelancers per country (%)

<PlotlyBarChart
  data={{
    url: 'freelancer_location.csv'
  }}
  xAxis="Country"
  yAxis="%"
/>

At least a third of them were charged with anti-state crimes.

## Charges faced by freelancers

<PlotlyBarChart
  data={{
    url: 'freelancers_charge.csv'
  }}
  xAxis="Charges"
  yAxis="Imprisoned"
/>

More than half of the imprisoned/disappeared media workers (56.9%) were detained between 2021 and this year. Only in 2023, **149 journalists were put in jail**.

## Imprisoned journalists by year
<PlotlyLineChart
  data={{
    url: 'per_year.csv'
  }}
  title="362 journalists and media workers were detained between 2021 and 2023"
  xAxis="year"
  yAxis="imprisoned"
/>

Recently, RSF's [2024 World Press Freedom research](https://rsf.org/en/index?year) found out that [75% of 180 countries currently face different levels of negative press freedom](https://datahub.io/@cheredia19/press-freedom-2024).

The high number of imprisoned or disappeared journalists, and the state of press freedom worldwide, call for reflection about the precarious condition of media workers amidst several conflicts and the rise of authoritative regimes around the world.

## Full list of imprisoned journalists

<FlatUiTable
  data={{
    url: 'imprisoned_journalists_2024.csv'
  }}
/>
**means missing or forcibly disappeared*. Sources: [CPJ](CPJ.org/data/imprisoned/), [RSF](rsf.org/en/barometer)
