# Instructions for archiving old workshop pages and updating for a new year

Create a new directory for the previous workshop and copy appropriate page files into that directory.
For example, the 2024 workshop website had the following files that needed to be copied into the 2024 directory:

- accomodations.md
- attendees.md
- contributions.md
- index.md
- restaurants.md
- schedule.md

Once that is done, you can use the previous year's files (that you just copied) as a template for the next year's workshop pages.
In each page, change the `year` in the front matter of the `.md` to the appropriate year.
Then, add a new entry in `_data/info.yml` under the workshop key for the current year.
For example, if you're organizing GPTP 2042, create a new key `gptp2042` with the same fields as `gptp2041` but updated appropriately.
The current layouts pull use these fields to populate details on the pages.