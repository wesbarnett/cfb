# CFB Rankings

This is a simple resume-based algorithm I developed for ranking college football
teams. It just uses wins and losses.

* Preaseason rankings can bias a poll's effectiveness. To overcome
  this, this algorithm uses randomly generated preaseason rankings. 
* In most polls a recent win or loss tends to be counted more strongly than
  earlier wins. This algorithm randomly shuffles the records of all
  games in order to alleviate this problem.
* Only wins and losses are counted in the algorithm
  (see below).  Strength of schedule is built in, because winning against a team
  ranked higher in an iteration moves your team up.

See [`docs/about.md`](docs/about.md) for more information on how to
compile the program and how the algorithm works. 

## Current rankings

After 11 weeks of play in the 2017-2018 season:

[Full rankings](output/rankings.csv)

 **Rank** |  |**Team**                  | **Record** | **Score**  
----------|--|---------------------------|------------|------------
1         | ![Alabama](logos/alabama.png) | Alabama                   | 10-0       |   0.631117
2         | ![Wisconsin](logos/wisconsin.png) | Wisconsin                 | 10-0       |   0.628449
3         | ![Miami (FL)](logos/miami-fl.png) | Miami (FL)                |  9-0       |   0.609664
4         | ![Clemson](logos/clemson.png) | Clemson                   |  9-1       |   0.608251
5         | ![UCF](logos/ucf.png) | UCF                       |  9-0       |   0.608147
6         | ![Oklahoma](logos/oklahoma.png) | Oklahoma                  |  9-1       |   0.606280
7         | ![Georgia](logos/georgia.png) | Georgia                   |  9-1       |   0.598680
8         | ![USC](logos/southern-california.png) | USC                       |  9-2       |   0.596910
9         | ![Notre Dame](logos/notre-dame.png) | Notre Dame                |  8-2       |   0.588513
10        | ![Penn State](logos/penn-st.png) | Penn State                |  8-2       |   0.587236
11        | ![Ohio State](logos/ohio-st.png) | Ohio State                |  8-2       |   0.586727
12        | ![Memphis](logos/memphis.png) | Memphis                   |  8-1       |   0.585124
13        | ![Boise State](logos/boise-st.png) | Boise State               |  8-2       |   0.583462
14        | ![Michigan](logos/michigan.png) | Michigan                  |  8-2       |   0.582554
15        | ![Oklahoma State](logos/oklahoma-st.png) | Oklahoma State            |  8-2       |   0.582454
16        | ![Washington State](logos/washington-st.png) | Washington State          |  9-2       |   0.582083
17        | ![South Florida](logos/south-fla.png) | South Florida             |  8-1       |   0.577032
18        | ![TCU](logos/tcu.png) | TCU                       |  8-2       |   0.574353
19        | ![Auburn](logos/auburn.png) | Auburn                    |  8-2       |   0.574293
20        | ![Washington](logos/washington.png) | Washington                |  8-2       |   0.571059
21        | ![San Diego State](logos/san-diego-st.png) | San Diego State           |  8-2       |   0.570475
22        | ![Toledo](logos/toledo.png) | Toledo                    |  8-2       |   0.569525
23        | ![Troy](logos/troy.png) | Troy                      |  8-2       |   0.566354
24        | ![Army](logos/army.png) | Army                      |  8-2       |   0.566037
25        | ![Michigan State](logos/michigan-st.png) | Michigan State            |  7-3       |   0.564476
