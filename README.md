# Climate Advisor

**EPW weather file explorer for architecture students**

Climate Advisor reads an EnergyPlus Weather (`.epw`) file and turns its 8 760 hourly records into charts that can be read, queried and exported. It is written for architecture students who have to understand a climate before they can design for it.

The interface is available in English, Portuguese (Portugal) and Polish (Poland).

## Features

- **Climate overview:** the shape of the year, monthly normals, ground temperatures and ASHRAE design conditions.
- **Data view:** an annual hourly carpet, monthly diurnal profiles, frequency distributions and duration curves for every variable in the file.
- **Wind:** wind roses by season and hour, roses limited to hours useful for ventilation, and the Beaufort scale.
- **Psychrometrics:** a psychrometric chart with the bioclimatic zones of Givoni, as presented by Manzano-Agugliaro et al. (2015).
- **Sun and sky:** a stereographic sun path with the year's temperatures plotted on it, daily solar energy and the clearness index.
- **Water and snow:** precipitation, observed weather events, snow cover, freeze–thaw cycles, wind-driven rain and rainwater yield.
- **Comfort:** adaptive comfort to EN 16798-1, degree days and annual temperature bands.

Every chart can be exported as PNG, and its underlying data as CSV.

## Use

Open the page in a current web browser and drop an `.epw` file onto it.

Climate Advisor does not supply, host or distribute weather files. Each user obtains them independently from a source of their choice (national meteorological services, research institutions or software developers publish them) and is responsible for observing the licence conditions that accompany them.

The application is a single self-contained HTML file with no dependencies and no build step.

## Privacy

Climate Advisor collects no personal data. Weather files are read and analysed entirely in the browser and are never uploaded. The page has no analytics, no tracking cookies and no externally loaded fonts or scripts. The only item stored on the device is the chosen interface language (`ca-lang` in local storage). Once loaded, the page makes no network request; a third party is contacted only if the visitor follows an external link.

The full privacy and legal notice is in the page footer, in all three languages.

## Disclaimer

Climate Advisor is an educational instrument provided "as is", without warranty. Its results describe a climate; they are not a building simulation and must not be used to demonstrate regulatory compliance without independent verification. The author does not supply or distribute weather files and is not responsible for their content, accuracy or licensing.

## Methods and sources

The methods and their sources are cited in the page footer (APA 7th edition), including ASHRAE (2017), EN 16798-1:2019, Givoni (1992, 1998), Manzano-Agugliaro et al. (2015) and the EnergyPlus documentation for the EPW format.

## Author

Carlos C. Duarte, Lisbon School of Architecture, Universidade de Lisboa (affiliation only; this is a personal project, not published by or on behalf of the University).
Contact: carlosfcduarte@edu.ulisboa.pt

## Licence

© 2026 Carlos C. Duarte. Released under the [European Union Public Licence v. 1.2](https://interoperable-europe.ec.europa.eu/collection/eupl/eupl-text-eupl-12) (EUPL-1.2). See [LICENSE](LICENSE). The EUPL is available in all official EU languages, each with equal legal value.
