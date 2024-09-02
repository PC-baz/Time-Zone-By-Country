
# Time Zones by Country

This repository contains a JSON file, `time-zone.json`, which lists the time zones for various countries and their territories. The data in this file is derived from the information available on the Wikipedia page ["List of time zones by country"](https://en.wikipedia.org/wiki/List_of_time_zones_by_country).

## time-zone.json

The `time-zone.json` file provides a detailed mapping of countries and their associated time zones, including specific regions or territories within each country. The data is structured to include the time offset from Coordinated Universal Time (UTC) and the relevant regions that fall under each time zone.

### Structure

Each entry in the JSON file includes:

- **Country Name**: The name of the country.
- **UTC Offset**: The time offset from UTC in the format "UTC±HH:MM".
- **Regions/Territories**: A list of regions or territories within the country that fall under the specified UTC offset.

### Example

\`\`\`json
{
    "France": {
        "UTC-10:00": ["Society Islands", "Tuamotus", "Austral Islands"],
        "UTC-09:30": ["Marquesas Islands"],
        "UTC-09:00": ["Gambier Islands"],
        "UTC-08:00": ["Clipperton Island"],
        "UTC-04:00": ["Guadeloupe", "Martinique", "Saint Barthélemy", "Saint Martin"],
        "UTC-03:00": ["French Guiana", "Saint Pierre and Miquelon"],
        "UTC+01:00": ["Metropolitan France"],
        "UTC+03:00": ["Mayotte", "Scattered Islands in the Indian Ocean"],
        "UTC+04:00": ["Réunion", "Crozet Islands"],
        "UTC+05:00": ["Kerguelen Islands", "Saint Paul and Amsterdam Islands"],
        "UTC+11:00": ["New Caledonia"],
        "UTC+12:00": ["Wallis and Futuna"]
    }
}
\`\`\`

### Countries Included

The JSON file includes time zone data for a wide range of countries, including but not limited to:

- **United States**
- **Russia**
- **Australia**
- **United Kingdom**
- **Canada**
- **Brazil**
- **India**
- **China**
- **Germany**

Each country’s entry includes multiple UTC offsets to account for regions that span across different time zones.

## Source

The data in this repository is based on the Wikipedia page ["List of time zones by country"](https://en.wikipedia.org/wiki/List_of_time_zones_by_country), ensuring that the information is both comprehensive and up-to-date.

## Contributions

Contributions to this repository are welcome. If you notice any inaccuracies or outdated information, please feel free to submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
