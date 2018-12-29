+++
abstract = "This paper discusses the problem of room usage optimization for university timetables: given a timetable, we want to optimize the room occupation by determining the events allocated to each room, while ensuring that the rooms have enough capacity to seat all people participating in those events. This paper contributes with two approaches to the problem of optimizing the timetable scheduled for each room. The first approach consists of a two-stage Integer Linear Programming (ILP) which applies a lexicographic optimization wherein the goal of the first stage is to maximize the number of students seated and that of the second stage is to optimize the room occupation. This is provably optimal, in both optimization criteria. However, it is computationally demanding, requiring significant computation time for large problems. To address this issue, we propose a second approach, consisting of a greedy algorithm. The algorithm assigns lectures to rooms greedily, according to a specific cost function that seeks to maximize the number of students seated. We show that the proposed cost function guarantees that the greedy algorithm performs within 63% of the total number of students. We apply both algorithms in a case study involving real data from Instituto Superior Técnico (IST), the engineering school from Universidade de Lisboa. Our results confirm that the greedy algorithm is two orders of magnitude faster than ILP when considering large data sets. Comparing the performance of the two methods we observe that the performance of the greedy algorithm, when compared to the ILP-based approach, is within 2% for the number of seated students and 34% for the room occupation. The GRASP algorithm is a good extension of the greedy algorithm, which is able to improve in 12% the quality of the solution (in terms of compactness) without adding significant CPU time. Overall, the two proposed approaches provide significant gains for both optimization criteria when compared to the current hand-made solutions."
authors = ["Alexandre Lemos","Francisco S. Melo","Pedro T. Monteiro","Inês Lynce"]
keyword=["University timetabling","Room usage optimization","Integer linear programming","Greedy algorithms"]
date = "2016-09-08"
image_preview = ""
math = true
publication_types = ["2"]
publication = ""
publication_short = ""
selected = true
title = "Room usage optimization in timetabling: A case study at Universidade de Lisboa"
#url_code = "https://github.com/ADDALemos/Compacter"
#url_dataset = "https://github.com/ADDALemos/Compacter"
url_pdf = "https://www.sciencedirect.com/science/article/pii/S2214716018301696?via%3Dihub"
#url_poster =  "papers/PosterINFORUM.pdf"
#url_project = ""
#url_slides = "#"
#url_video = "#"

#[[url_custom]]
#name = "Custom Link"
#url = "http://www.example.org"

# Optional featured image (relative to `static/img/` folder).
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"


+++
