# Tube Timings
List of times between tube stations, in a machine readable format, based on the TfL working timetables. Data may be inaccurate.

### Included data
- Only tube lines have been included in this dataset
- Stations have been grouped based on TfL station IDs (for example, Paddington is counted twice)
- Metropolitan line fast and semi-fast timings have been included
- Services outside of the majority of operating times have been excluded (Piccadilly line at Turnham Green, Metropolitan line Rickmansworth to Croxley)
- Where multiple lines serve the same set of stations:
    - If they make identical stops (Northern and Bakerloo lines between Waterloo and Charing Cross), only one route is included
    - If one route skips stops (Metropolitan and Jubilee lines between Wembley Park and Baker Street), both routes have been included

### Format of the dataset
All timings are given in decimal minutes, to 2 decimal places, or exact values. Timings are given for both directions between station pairs (they do differ sometimes).

The dataset is provided in two forms. `data.txt` contains TfL station IDs, while `data_text.txt` contains English shorthand identifier - these identifiers are **not** consistent within the file, and do contain spelling errors.

Both formats are formatted with a station pair on each line, in the format of `[start] [end] [time]`

## License
Tube Timings is licensed under a
Creative Commons Attribution-ShareAlike 4.0 International License.

You should have received a copy of the license along with this
work.  If not, see <http://creativecommons.org/licenses/by-sa/4.0/>.
