## Operating systems project #1

### Usage: ./corona [-h] [FILTERS] [COMMAND] [LOG [LOG2 [...]]

##### Commands (only one):
- **infected** — counts total number of infected people.
- **merge** — prints multiple files as one - header is only printed once.
- **gender** — prints number if infected by gender.
- **age** — prints number of infected by age.
- **daily** — prints number of infected each day.
- **monthly** — prints number of infected each month.
- **yearly**— prints number of infected each year.
- **countries** —  prints number of infected in each country (excluding CZ).
- **districts** — prints number of infected in each district.
- **regions** — prints number of infected in each region.

##### Filters - can combine multiple filters (each can only be entered once):
- **-a DATETIME** — only process records after given date (including given date). DATETIME format: YYYY-MM-DD.
- **-b DATETIME** — only process records before given date (including given date).
- **-g GENDER** — only process records of the given gender. GENDER inputs: M (male), Z (female).
- **-s [WIDTH]** commands ***gender, age, daily, monthly, yearly, countries, districts and regions*** print data using graphs.
                 width is an optional parameter, that sets the width of the longest line of the histogram.
                 if width isn't included, each # corresponds to a default value

#### Input files
Input files must be in ***.csv*** format.
These files can also be bundled in ***.gz or .bz2*** archives.

Sample input files can be found here:
https://onemocneni-aktualne.mzcr.cz/api/v2/covid-19