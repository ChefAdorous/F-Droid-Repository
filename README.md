# F-Droid Repository Tracker

This repository automatically tracks and updates a list of F-Droid repositories. It provides an up-to-date overview of various F-Droid repositories, including their names, URLs, last update times, app counts, and descriptions.

## Tracked Repositories

Below is a table of the currently tracked F-Droid repositories. This table is automatically updated every 15 minutes.

<!-- START_FDROID_REPO_TABLE -->

| name                                     | url                                       | last_updated        |   app_count | description   |
|:-----------------------------------------|:------------------------------------------|:--------------------|------------:|:--------------|
| mirror of f-droid.org                    | https://fdroid.org/repo/                  | 2025-05-12 09:34:49 |           0 | N/A           |
| My First F-Droid Archive Demo            | https://f-droid.org/archive/              | 2025-05-12 09:34:49 |           0 | N/A           |
| Guardian Project Official App Repository | https://guardianproject.info/fdroid/repo/ | 2025-05-12 09:34:50 |           0 | N/A           |
| IzzyOnDroid F-Droid Repository           | https://apt.izzysoft.de/fdroid/repo/      | 2025-05-12 09:34:51 |           0 | N/A           |

<!-- END_FDROID_REPO_TABLE -->

## About This Project

This project uses GitHub Actions to automatically fetch and update information about F-Droid repositories. The workflow runs every 15 minutes, ensuring that the information stays current.

### Features

- Automatic updates every 15 minutes
- Removal of duplicate repositories
- Formatted table in README for easy viewing
- JSON data file for programmatic access
- Self-updating workflow

### How It Works

1. The GitHub Action workflow runs on a schedule.
2. It fetches data from various F-Droid repository sources.
3. The data is processed to remove duplicates and invalid entries.
4. The README.md file is updated with a formatted table of repository information.
5. A JSON file is also updated with the repository data.
6. Changes are committed and pushed back to the repository.

### Contributing

If you know of an F-Droid repository that should be included, please open an issue or submit a pull request to add it to the list of URLs in the workflow file.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
