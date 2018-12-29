+++
# Date this page was created.
date = "2017-02-27"

# Project title.
title = "Room Usage Optimization in Timetabling:  A Case Study at Universidade de Lisboa"

# Project summary to display on homepage.
summary = "This paper discusses the problem of room usage usage optimization for university timetables. Given a timetable, the goal is to optimize the room occupation by changing the events allocated to each room. The methods proposed do not solve the problem from scratch and so no curriculum constraints are handled. The main objective is to optimize the timetable scheduled for each room without changing the already defined time slots for each lecture. This type of optimization is important since room space is a precious commodity. The proposed algorithms optimize the space allocation in terms of capacity (seating students) and compactness (reducing the number of gaps in the timetable for each room). This problem is analysed and discussed for the case study of Instituto Superior Técnico (IST), the engineering school from Universidade de Lisboa. At IST, the generation of timetables is still hand-made and therefore prone to optimization. This paper proposes a two-stage Integer Linear Programming (ILP) method to optimize the room usage. In the first stage, the goal is to assign lectures to rooms respecting their capacity. The second stage minimizes the gaps by reassigning the lectures to rooms (ensuring the same quality in terms of seated students found in the first stage). This implementation is able, in one hand, to prove optimality in both stages; on the other hand, it is quite time consuming. To address this issue, in this paper we also propose a greedy algorithm. The best cost function used to guide the algorithm is proved to be monotone, positive and sub-modular. Therefore, the results obtained are guaranteed to be within 63 percente of the optimal. The proposed solutions are tested using data from the lectures of Instituto Superior Técnico taught on the Taguspark and Alameda campus in the academic year of 2016/2017. The greedy algorithm is two orders of magnitude faster than ILP when considering large data sets. In terms of seated students, the best cost function is on average 2 percente below the optimal value. The timetable for a given room can be evaluated in terms of compactness (the number of transitions from free to occupied). Considering this metric, the solution provided by a greedy algorithm is only 1.2x worse than the optimal value for the Taguspark data sets. For the Alameda data sets, the solution obtained by ILP implementation is 0.7x better (optimal solution) than the greedy algorithm. However, the ILP implementation is, in the worst case, 5 orders of magnitude slower. Overall, both implementations provide significant gains for both optimization criteria when compared with the current hand-made approaches."

# Optional image to display on homepage (relative to `static/img/` folder).
#image_preview = "bubbles.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["ilp"]

# Optional external URL for project (replaces project detail page).
external_link = "https://github.com/ADDALemos/Compacter/"

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++
