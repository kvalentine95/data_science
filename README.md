<h1>JSON Exercises using the data about projects funded by the World Bank</h1>
<h2>Source</h2>
<p>Data source: http://jsonstudio.com/resources/</p>
<h2>Deliverables</h2>
<ol>
  <li>Find the 10 countries with most projects</li>
  <li>Find the top 10 major project themes (using column 'mjtheme_namecode')</li>
  <li>In 2. above you will notice that some entries have only the code and the name is missing. Create a dataframe with the missing names filled in</li>
</ol>
<h2>Approach</h2>
<ol>
  <li>Import all necessary packages(numpy, json, pandas) and read json file into a dataframe to inspect it</li>
  <li>Obtain the top-10 most frequent values in the column that shows country names</li>
  <li>Inspect and normalize any nested values in 'mjtheme_namecode'</li>
  <li>Obtain top-10 project themes with their names and codes</li>
  <li>Sort the project codes and names to ensure that missing values are aggregated for every project code</li>
  <li>Substitute empty cells with NaN values and replace them with correct project names</li>
  <li>Produce the top-10 project themes with their names</li>
</ol>
<h2>Summary of Results</h2>
<p> The top-10 countries with most projects are shown below: </p>
<table>
  <tr>
    <th>Country</th>
    <th>Number of Projects</th>
  </tr>
   <tr>
    <th>People's Republic of China </th>
    <th>19</th>
  </tr>
   <tr>
    <th>Republic of Indonesia </th>
    <th>19</th>
  </tr>
   <tr>
    <th>Socialist Republic of Vietnam</th>
    <th>17</th>
  </tr>
   <tr>
    <th>Republic of India</th>
    <th>16</th>
  </tr>
  <tr>
    <th>Republic of Yemen</th>
    <th>13</th>
  </tr>
  <tr>
    <th>Kingdom of Morocco </th>
    <th>12</th>
  </tr>
  <tr>
    <th>People's Republic of Bangladesh</th>
    <th>12</th>
  </tr>
  <tr>
    <th>Nepal</th>
    <th>12</th>
  </tr>
  <tr>
    <th>Republic of Mozambique</th>
    <th>11</th>
  </tr>
   <tr>
    <th>Africa</th>
    <th>11</th>
  </tr>
</table>
<p>The top-10 most popular project themes are shown below: </p>
<table>
  <tr>
    <th>Project Theme</th>
    <th>Number of Instances</th>
  </tr>
   <tr>
    <th>Environment and natural resources management</th>
    <th>250</th>
  </tr>
   <tr>
    <th>Rural development </th>
    <th>216</th>
  </tr>
   <tr>
    <th>Human development </th>
    <th>210</th>
  </tr>
   <tr>
    <th>Public sector governance</th>
    <th>199</th>
  </tr>
  <tr>
    <th>Social protection and risk management</th>
    <th>168</th>
  </tr>
  <tr>
    <th>Financial and private sector development </th>
    <th>146</th>
  </tr>
  <tr>
    <th>Social dev/gender/inclusion</th>
    <th>130</th>
  </tr>
  <tr>
    <th>Trade and integration </th>
    <th>77</th>
  </tr>
  <tr>
    <th>Urban development</th>
    <th>50</th>
  </tr>
   <tr>
    <th>Economic management</th>
    <th>38</th>
  </tr>
</table>
