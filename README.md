# Pewlett Hackard Analysis
In preparation for the advancing age of the baby boomer generation, Pewlett Hackard (PH) is developing a new program for retiring employees. Rather than retiring, eligible employees would be retained as part-time employees to educate and mentor their successors. As part of the development process, this SQL program answers how many upcoming retirees this would impact as well as who is eligible to participate in the mentorship program as a successor.

### Results
| Retiring Employees by Title | Employees Eligible for Mentorship |
|-----------------------------|-----------------------------------|
|![Retiring_emps.png](https://github.com/kaileymd/Pewlett-Hackard-Analysis/blob/main/Images/Retiring_emps.png)|![Mentorship_eligibility](https://github.com/kaileymd/Pewlett-Hackard-Analysis/blob/main/Images/Mentor_eligibility.png)|

### Summary
When considering the retirement of baby boomers and the implementation of the mentorship program, PH should consider:
- About 90,000 of their 300,000 total employees are retiring - that's 30% of their workforce.
- According to [Pew Research](https://www.pewresearch.org/fact-tank/2019/07/24/baby-boomers-us-labor-force/) many baby boomers are choosing to stay in the labor force longer than previous generations. This increases the odds that the actual retirement rate PH will see will be lower than what this analysis has indicated.
- Barring their personal choices, the amount of individuals retiring each year is consistent: ![Retire_groups](https://github.com/kaileymd/Pewlett-Hackard-Analysis/blob/main/Images/Retire_groups.png)
- The number of retirees vs. mentees. When looking at the two most populous titles - Senior Engineer and Senior Staff - there is a clear mismatch between the group sizes for those retiring compared to those they would be mentoring. 
  - For example, 29,414 Senior Engineers are retiring, while only 529 are eligible for the mentorship. PH's mentor position needs would be filled if only 2% of retirees join the program.

### Conclusion
In conclusion, PH will either have to widen eligibility for the mentorship program, hire new talent, or both to fill the 90,398 total roles that will become vacant if the baby boomer generation retires on time. This analysis recommends both, particularly since none of PH's employees were borth after 1965:

![emps_dob](https://github.com/kaileymd/Pewlett-Hackard-Analysis/blob/main/Images/emps_dob.png)
