# CPS % Enrollment by Race

This repository includes the RShiny code and data for an interactive map of CPS Enrollment by Race in 2019.

Input data obtained from <a href="https://www.isbe.net/pages/illinois-state-report-card-data.aspx"> Illinois Report Card's Report Card Data Library </a>.
<p>
  Shape File from the <a href = "https://data.cityofchicago.org/Facilities-Geographic-Boundaries/Boundaries-Community-Areas-current-/cauq-8yn6"> City of Chicago </a>
  <p>
    <h3>
<b>Shiny Map</b></h3>
</p>
Link to <a href = "https://yiningw.shinyapps.io/CPSRaceEnroll/"> Shiny App </a><p><p>
<img src = "https://github.com/yining-w/CPSRaceEnrollment/blob/master/map%20screenshot.jpg"> </img>
<p>
  <h3>
<b>Analysis</b><p></h3>
<i> app.R </i> - Code for map using RLeaflet 
  <p>
  <i> enroll_race_info.csv </i> - dataset. Includes school code, school address and lat-long info, school name, year (2011 - 2019), % enrollment per race.
