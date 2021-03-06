### 2015 UP Panchayat General Election Results

We scraped 2015 UP Panchayat General Election Results posted at [UP State Election Commission](http://sec.up.nic.in/ElecLive/WinnerList.aspx).

The website offers two dropdowns (one for district, one for post) through which all the results are accessible.

Type of posts = Area panchayat chief, district panchayat president, district panchayat member, area panchayat member, gram panchayat head.

For area panchayat chief and district panchayat president, there is only have one file each.

### Script

[Script](scripts/https://github.com/in-rolls/up-2015-panchayat-ge-results/blob/master/scripts/WinnerList.ipynb)

### Data

[Data](data/)

The data format varies slightly by post.

For area panchayat chief, the header =

```District, Kshetra Panchayat,	Reservation of post,	Candidate	Father / husband,	Candidate's reservation,	educational qualification,	Gender,	Mobile number,	Received valid vote,	Votes received,	vote %,	result```

For district panchayat president, the header =

```District Panchayat,	Reservation of post,	Candidate	Father / husband, Candidate's reservation,	educational qualification,	Gender, Mobile number, Received valid vote, Votes received, vote %, result```

For district panchayat member, the header =

```District Panchayat Ward,	Reservation of post,	Candidate	Father / husband,	Candidate's reservation,	educational qualification,	Gender,	Mobile number,	Received valid vote,	Votes received,	vote %,	result```

For area panchayat member, the header =

```The block, Kshetra Panchayat Ward,	Reservation of post, Candidate	Father / husband, Candidate's reservation, educational qualification,	Gender,	Mobile number,	Received valid vote,	Votes received,	vote %, result```

For gram panchayat head, the header =

```The block,	Village Panchayat,	Reservation of post,	Candidate	Father / husband,	Candidate's reservation,	educational qualification,	Gender,	Mobile number,	Received valid vote,	Votes received	vote %,	result```
