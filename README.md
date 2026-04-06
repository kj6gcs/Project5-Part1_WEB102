# Web Development Project 5 - _Orbital Watch_

Submitted by: **Robby Wideman**

This web app: **Orbital Watch uses The Space Devs Launch Library 2 public API to fetch real upcoming space launch data, including mission names, providers, launch dates, and locations.**

Time spent: **5** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] **The site has a dashboard displaying a list of data fetched using an API call**
  - The dashboard should display at least 10 unique items, one per row
  - The dashboard includes at least two features in each row
- [x] **`useEffect` React hook and `async`/`await` are used**
- [x] **The app dashboard includes at least three summary statistics about the data**
  - The app dashboard includes at least three summary statistics about the data, such as:
    - _Total Launches_
    - _Launch Providers_
    - _Launches With Missions_
    - _Matching Current Filters_
- [x] **A search bar allows the user to search for an item in the fetched data**
  - The search bar **correctly** filters items in the list, only displaying items matching the search query
  - The list of results dynamically updates as the user types into the search bar
- [x] **An additional filter allows the user to restrict displayed items by specified categories**
  - The filter restricts items in the list using a **different attribute** than the search bar
  - The filter **correctly** filters items in the list, only displaying items matching the filter attribute in the dashboard
  - The dashboard list dynamically updates as the user adjusts the filter

The following **optional** features are implemented:

- [x] Multiple filters can be applied simultaneously
- [x] Filters use different input types
  - e.g., as a text input, a dropdown or radio selection, and/or a slider
- [x] The user can enter specific bounds for filter values

The following **additional** features are implemented:

- [x] Added a clear filters button to reset filters to default, enabling users to start a clean search without having to reload the entire page.
- [x] Enlarged placeholder text within dynamic search bar to draw user's attention to that as a ssearch option without having to use filters or search the entire page individually.

## Video Walkthrough

Here’s a video walkthrough of the implemented required features:

<p align="center">
  <a href="https://www.youtube.com/watch?v=_8-BF_UXPbE" target="_blank" rel="noopener noreferrer">
    <img src="https://img.youtube.com/vi/_8-BF_UXPbE/hqdefault.jpg" width="600" alt="Video Walkthrough Thumbnail">
  </a>
</p>

<p align="center">
  <img src="/project5Part1Walkthrough.gif" alt="Project Walkthrough">
</p>

GIF created with [ScreenToGif](https://www.screentogif.com/) for Windows.

## Notes

I had originally wanted to do something with an orbital objects tracking reference (I'm a space nerd!), but the fetch linke I wanted to use was not working properly with my app build. So, I changed gears, keeping it space-oriented, but changed over to planned space launches.

## License

    Copyright 2026 Robby Wideman

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
