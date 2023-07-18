#
<p style="color:orangered">India Portal 2.0</p>
<p style="font-size:20px">
Project Review Meeting for june 2023
K&A team 5 july 2023
</p>

# 
<p style=";color:orangered">Agenda</p>
<ul style="font-size:20px">
<li>Milestone 1 Scope of Work</li>
<li>Data Analysis</li>
<li>Current Project Team Organization</li>
<li>SW Architecture View</li>
<li>Going forward</li>
<li>A glimpse of future milestones</li>
</ul>

<!-- 
+ Milestone 1 Scope of Work
+ Data Analysis
+ Current Project Team Organization
+ SW Architecture View
+ Going forward
+ A glimpse of future milestones -->

# 
<div style="display:flex;width:100%;height:100%;border:4px solid orangered">
  <div style="width:50%;height:700px;align-item:center;padding-top:35%;;color:orangered;font-size:40px">Scope of Work</div><div style="width:50%;height:700px;background-color:teal;align-item:center;padding-top:35%;"><p style="font-size:15px">Understanding of the Project</p></div>
</div>

# 
<h3 style="font-size:40px;color:orangered">Milestone</h3>
<img src="4.png" style="border:10px solid orangered">

#
<h3 style="font-size:40px;color:orangered">Milestone 1 RoadMap</h3>
<img src="5.png" style="border:10px solid orangered" >

# 
<div style="display:flex;width:100%;height:100%;border:4px solid orangered">
  <div style="width:50%;height:700px;align-item:center;padding-top:32%;font-size:40px"><h2 style=";color:orangered" >Milestone1</h2><p>Requirement Analysis</p></div><div style="width:50%;height:700px;background-color:teal;align-item:center;padding-top:35%;"><p style="font-size:15px">Theme Prototype Ready</p></div>
</div>

# 
<h3 style="font-size:40px;color:orangered">Requirement Gathering...Data Source Analysis..1/2</h3>
<div style="font-size:20px">
<p>Total Data Source : 23</p>
<p>Not available : 8 </p>
<p>Available and Analysed : 15</p>
</div>

# 
<p style="color:orangered;font-size:40px">Data Source:API Not available</p>
<table style="font-size:20px" >
<tr>
<td>S.No.</td>
<td>Component</td>
<td>Sources</td>
<td>Remarks</td>
</tr>
<tr>
<td>1</td>
<td>services</td>
<td>Various Digital services Delivery <br> Portals/Applications(Umang,Service Pus,NGSP etc)</td>
<td>through APIs</td>
</tr>
<tr>
    <td>2</td>
    <td>schemes</td>
    <td>Platforms like Haqdarshak, EasyGov,Schemopedia, <br>Digital Empowerment Foundation,etc <br> Portals/Applications(Umang,Service Pus,NGSP etc)</td>
    <td>One Platform would be selected for integration, through APIs</td>
</tr>
<tr>
    <td>3</td>
    <td>infographics</td>
    <td>MyGov,DataGov,PIB</td>
    <td>thorough APIs</td>
</tr>
<tr>
    <td>4</td>
    <td>news</td>
    <td>PIB,DDNews,NewsonAir etc</td>
    <td>through APIs and RSS Feeds</td>
</tr>
<tr>
    <td>5</td>
    <td>webcasts</td>
    <td>webcast.gov.in</td>
    <td>through APIs</td>
</tr>
<tr>
    <td>6</td>
    <td>state contact directory</td>
    <td>S3Waas</td>
    <td>State level contact directory will be created as and when the departments onboard,through APIs</td>
</tr>
<tr>
    <td>7</td>
    <td>acts and rules</td>
    <td>indiacode.nic.in</td>
    <td>through APIs</td>
</tr>
<tr>
    <td>8</td>
    <td>Visualization</td>
    <td>DataGov</td>
    <td>through APIs</td>
</tr>
</table>

#
<h3 style="font-size:40px;color:orangered">Data Source:API analysed...2/2</h3>
<table style="font-size:12px">
<tr>
<td>S.No.</td>
<td >Component</td>
<td >Source</td>
<td >Mode</td>
<td >Search API</td>
<td >Reference website</td>
<td >K&A Remarks</td>
</tr>
<tr >
<td>7</td>
<td>ecourts contact <br> directory <br>(judges)</td>
<td>S3WaaS</td>
<td>through APIs</td>
<td>Make at NPI</td>
<td>https://ecourts.gov.in/</td>
<td>Available and being analysed </td>
</tr>
<tr>
    <td>8</td>
    <td>knowindia- <br> tourist places</td>
    <td>S3WaaS</td>
    <td>through APIs</td>
    <td>Make at NPI</td>
    <td>https://aliraipr.nic.in/en/tourist-places</td>
    <td>Available and Analysed </td>
</tr>
<tr>
    <td>9</td>
    <td>knowindia- <br> accomodation</td>
    <td>S3WaaS</td>
    <td>through APIs</td>
    <td>Make at NPI</td>
    <td>https://agra.nic.in/acco <br> modation/html/https://alir <br> aipr.nic.in/en/where-t <br> o-stay</td>
    <td>Available and Analysed </td>
</tr>
<tr>
    <td>10</td>
    <td>knowindia- <br> photo gallary</td>
    <td>S3WaaS</td>
    <td>through APIs</td>
    <td>Make at NPI</td>
    <td>https://agra.nic.in/acco <br> modation/html/https://alir <br> aipr.nic.in/en/where-t <br> o-stay</td>
    <td>Available and Analysed </td>
</tr>
<tr>
    <td>11</td>
    <td>knowindia- <br> photo gallary</td>
    <td>S3WaaS</td>
    <td>through APIs</td>
    <td>Make at NPI</td>
    <td>https://agra.nic.in/acco <br> modation/html/https://alir <br> aipr.nic.in/en/where-t <br> o-stay</td>
    <td>Available and Analysed </td>
</tr>
<tr>
    <td>12</td>
    <td>knowindia- <br> produce</td>
    <td>S3WaaS</td>
    <td>through APIs</td>
    <td>Make at NPI</td>
    <td>https://agra.nic.in/acco <br> modation/html/https://alir <br> aipr.nic.in/en/where-t <br> o-stay</td>
    <td>Available and Analysed </td>
</tr>
<tr>
    <td>13</td>
    <td>knowindia- <br> helpline</td>
    <td>S3WaaS</td>
    <td>through APIs</td>
    <td>Make at NPI</td>
    <td>https://agra.nic.in/acco <br> modation/html/https://alir <br> aipr.nic.in/en/where-t <br> o-stay</td>
    <td>Available and Analysed </td>
</tr>
<tr>
    <td>14</td>
    <td>knowindia- <br> public utilities</td>
    <td>S3WaaS</td>
    <td>through APIs</td>
    <td>Make at NPI</td>
    <td>https://agra.nic.in/acco <br> modation/html/https://alir <br> aipr.nic.in/en/where-t <br> o-stay</td>
    <td>Available and Analysed </td>
</tr>
<tr>
    <td>15</td>
    <td>blogs</td>
    <td>MyGov, <br>DataGov</td>
    <td>through APIs</td>
    <td></td>
    <td>https://agra.nic.in/acco <br> modation/html/https://alir <br> aipr.nic.in/en/where-t <br> o-stay</td>
    <td>Available and Analysed. Findings shared with Pankaj/Ravi </td>
</tr>
</table>

#
<h3 style="font-size:40px;color:orangered">Data Source: Summary</h3>
<ol style="font-size:20px">
  <li>Classification of data into master and transactional
     <ol style="list-style-type: lower-alpha;" >
       Master
       <li>The data which is largely static like state list, district list,ministry list</li> 
       <ol style="list-style-type: lower-roman;">
       Transactional
       <li  >The data which changes quite often like Lok Sabha/Rajya Sabha members,who'who,judges etc</li>
    </ol>
    </ol>
  </li>
  <li>
  Conflicting masters
   <ol style="list-style-type: lower-alpha;">
     <li>
     which master IGOD or S3WAAS to refer for state and district list?
     </li>
   </ol>
  </li>
</ol>

# 
<h3 style="font-size:40px;color:orangered">Design Approach</h3>
<p style="font-size:20px">First Ingest Master Data</p>
<p style="font-size:20px">Resolve conflicts between Masters</p>
<p style="font-size:20px">Link to ingested masters while ingested masters while ingesting transactional dta</p>

# 
<div style="display:flex;width:100%;height:100%;border:4px solid orangered">
  <div style="width:50%;height:700px;align-item:center;padding-top:32%;font-size:40px"><h2 style=";color:orangered" >S3WAAS</h2><p>Data Analysis</p></div><div style="width:50%;height:700px;background-color:teal;align-item:center;padding-top:35%;"></div>
</div>

#
<h3 style="font-size:40px;color:orangered">Data Source:Findings(S3WAAS)..1/2</h3>
<table style="font-size:20px">
 <tr>
   <td>#</td>
   <td>S3WAAS API</td>
   <td>Proposed facets of search</td>
   <td>free text search</td>
   <td>Nature</td>
   <td>Remarks</td>
 </tr>
 <tr>
   <td>1.</td>
   <td>state list</td>
   <td></td>
   <td></td>
   <td>Master</td>
   <td>Conflicts with IGOD state master</td>
 </tr>
<tr>
   <td>2.</td>
   <td>District list</td>
   <td>stateName</td>
   <td></td>
   <td>Master</td>
   <td>Conflicts with IGOD district master</td>
 </tr>
 <tr>
   <td>3.</td>
   <td>district who is who</td>
   <td>StateName,districtName,category,designation</td>
   <td>Name(Title)</td>
   <td>Transactional</td>
   <td>Duplication of content between who'who and Directory List</td>
 </tr>
 <tr>
   <td>4.</td>
   <td>district contact directory</td>
   <td>StateName,districtName,category,designation</td>
   <td>Name(Title)</td>
   <td>transactionalr</td>
   <td>Duplication of content between who'who and Directory List</td>
 </tr>
 <tr>
   <td>5.</td>
   <td>state category directory</td>
   <td></td>
   <td></td>
   <td>Transactionalr</td>
   <td>Not available</td>
 </tr>
 <tr>
   <td>6.</td>
   <td>ecourts contact directory(judges) </td>
   <td></td>
   <td></td>
   <td>Transactional</td>
   <td>Under Analysis</td>
 </tr>
 <tr>
   <td>7.</td>
   <td>ecourts contact directory(judges) </td>
   <td></td>
   <td></td>
   <td>Transactional</td>
   <td>Under Analysis</td>
 </tr>
 <tr>
   <td>8.</td>
   <td>ecourts contact directory(judges) </td>
   <td></td>
   <td></td>
   <td>Transactional</td>
   <td>Under Analysis</td>
 </tr>
 </table>

 #
<h3 style="font-size:40px;color:orangered">Data Source:Findings(S3WAAS)..1/2</h3>
<table style="font-size:20px">
 <tr>
   <td>#</td>
   <td>S3WAAS API</td>
   <td>Proposed facets of search</td>
   <td>free text search</td>
   <td>Nature</td>
   <td>Remarks</td>
 </tr>
 <tr>
   <td>9.</td>
   <td>state list</td>
   <td></td>
   <td></td>
   <td>Master</td>
   <td>Conflicts with IGOD state master</td>
 </tr>
<tr>
   <td>10.</td>
   <td>District list</td>
   <td>stateName</td>
   <td></td>
   <td>Master</td>
   <td>Conflicts with IGOD district master</td>
 </tr>
 <tr>
   <td>11.</td>
   <td>district who is who</td>
   <td>StateName,districtName,category,designation</td>
   <td>Name(Title)</td>
   <td>Transactional</td>
   <td>Duplication of content between who'who and Directory List</td>
 </tr>
 <tr>
   <td>12.</td>
   <td>district contact directory</td>
   <td>StateName,districtName,category,designation</td>
   <td>Name(Title)</td>
   <td>transactionalr</td>
   <td>Duplication of content between who'who and Directory List</td>
 </tr>
 <tr>
   <td>13.</td>
   <td>state category directory</td>
   <td></td>
   <td></td>
   <td>Transactionalr</td>
   <td>Not available</td>
 </tr>
 </table>

 # 
<div style="display:flex;width:100%;height:100%;border:4px solid orangered">
  <div style="width:50%;height:700px;align-item:center;padding-top:32%;font-size:40px"><h2>IGOD</h2><p>Data Analysis</p></div><div style="width:50%;height:700px;background-color:teal;align-item:center;padding-top:35%;"></div>
</div>

 #
<h3 style="font-size:40px;color:orangered">Data Source:Findings(IGOD)..1/2</h3>
<table style="font-size:20px" >
 <tr>
   <td>#</td>
   <td>IGOD API</td>
   <td>Proposed facets of search</td>
   <td>free text search</td>
   <td>Nature</td>
   <td>Remarks</td>
 </tr>
 <tr>
   <td>1.</td>
   <td>state list</td>
   <td></td>
   <td></td>
   <td>Master</td>
   <td>Conflicts with IGOD state master</td>
 </tr>
<tr>
   <td>2.</td>
   <td>District list</td>
   <td>stateName</td>
   <td></td>
   <td>Master</td>
   <td>Conflicts with IGOD district master</td>
 </tr>
 <tr>
   <td>3.</td>
   <td>district who is who</td>
   <td>StateName,districtName,category,designation</td>
   <td>Name(Title)</td>
   <td>Transactional</td>
   <td>Duplication of content between who'who and Directory List</td>
 </tr>
 <tr>
   <td>4.</td>
   <td>district contact directory</td>
   <td>StateName,districtName,category,designation</td>
   <td>Name(Title)</td>
   <td>transactionalr</td>
   <td>Duplication of content between who'who and Directory List</td>
 </tr>
 <tr>
   <td>5.</td>
   <td>state category directory</td>
   <td></td>
   <td></td>
   <td>Transactionalr</td>
   <td>Not available</td>
 </tr>
 <tr>
   <td>6.</td>
   <td>state category directory</td>
   <td></td>
   <td></td>
   <td>Transactionalr</td>
   <td>Not available</td>
 </tr>
 <tr>
   <td>7.</td>
   <td>state category directory</td>
   <td></td>
   <td></td>
   <td>Transactionalr</td>
   <td>Not available</td>
 </tr>
 <tr>
   <td>8.</td>
   <td>state category directory</td>
   <td></td>
   <td></td>
   <td>Transactionalr</td>
   <td>Not available</td>
 </tr>
 </table>

#
<h3 style="font-size:40px;color:orangered">Data Source:Findings(IGOD)..2/2</h3>
<table style="font-size:20px">
<tr>
    <td>#</td>
    <td>IGOD API</td>
    <td>Proposed facets of search</td>
    <td>free text search</td>
    <td>Nature</td>
    <td>Remarks</td>
</tr>
<tr>
   <td>1.</td>
   <td>state list</td>
   <td></td>
   <td></td>
   <td>Master</td>
   <td>Conflicts with IGOD state master</td>
</tr>
<tr>
   <td>2.</td>
   <td>District list</td>
   <td>stateName</td>
   <td></td>
   <td>Master</td>
   <td>Conflicts with IGOD district master</td>
</tr>
</table>

# 
<div style="display:flex;width:100%;height:100%;border:4px solid orangered">
  <div style="width:50%;height:700px;align-item:center;padding-top:32%;"><h2>SANSAD</h2><p>Data Analysis</p></div><div style="width:50%;height:700px;background-color:teal;align-item:center;padding-top:35%;"></div>
</div>

#
<h3 style="font-size:40px;color:orangered">Data Source: sansad Findings()..1</h3>
<table style="font-size:20px">
 <tr>
   <td>#</td>
   <td>API</td>
   <td>Proposed facets of search</td>
   <td>free text search</td>
   <td>Nature</td>
   <td>Remarks</td>
 </tr>
 <tr>
   <td>1.</td>
   <td>state list</td>
   <td></td>
   <td></td>
   <td>Master</td>
   <td>Conflicts with IGOD state master</td>
 </tr>
<tr>
   <td>2.</td>
   <td>District list</td>
   <td>stateName</td>
   <td></td>
   <td>Master</td>
   <td>Conflicts with IGOD district master</td>
 </tr>
 </table>

#
<p style="font-size:20px;color:orangered">Frontend Activities being done so far
<ul style="list-style:disc;font-size:20px; ">
<li>A faceted search prototype is develped and demonstrated for s3waas who's who</li>
<li>CMS use cases</li>
<ul style="list-style:square">
<li>Tag workflow requiring approval by moderator</li>
<li>Tag workflow without approval(unmoderated)</li>
<li>Masters tables</li>
</ul>
</ul>
<p style="font-size:20px">Upcoming</p>
<p style="font-size:20px">UI MockUps(Landing page)</p>
<p style="font-size:20px">CMS use case</p>

#
<p style="font-size:40px;color:orangered;">CMS use cases</p>
<p style="font-size:30px">Functional Requirements</p>
<p style="font-size:20px" >newsletters </p>
<p style="font-size:20px">MetaData Section(SEO)</p>
<p style="font-size:20px">content for National Celebrations (Republic day and Independence day)</p>
<p style="font-size:20px">spotlights </p>
<p style="font-size:20px">page management(for pages like contact us, about us etc) and Pages based on user profiling </p>
<p style="font-size:20px"> adding custom attributes to the data like Tags,</p>
<p style="font-size:20px">Audit management in Strapi(perhaps available in enterprise version)</p>
<p style="font-size:20px">API integration</p>
<p style="font-size:20px">adding People Group</p>
<br>
<br>
<p style="font-size:20px">Non Functional Requirements</p>
<p style="font-size:20px"> Third party authentication implementation using keycloak.</p>
<p style="font-size:20px"> User role based management CMS.</p>
<p style="font-size:20px"> Group user for api allowance.</p>
<p style="font-size:20px"> Deploy using Docker/kubernates.</p>
<p style="font-size:20px"> Multiple instances of strpi.</p>
<p style="font-size:20px">Dashboards</p>
<p style="font-size:20px">Pipeline Workflow(like source of each pipeline..)</p>


# 
<p style="font-size:40px;color:orangered;" > Overview of pipeline for one API of one source </p>
<img src="23.png" style="border:10px solid orangered">

#
<p style="font-size:40px;color:orangered;">Backend Activities Done so far</p>
<ul style="font-size:20px">
  <li>IGOD state pipeline</li>
  <li>IGOD state data acquisition task, data mapper task</li>
  <li>Prototyping ongoing for a generic data store pipeline using</li>
  <li>Topic and Kafka connect</li>
  <li>Next</li>
  <li>S3WAAS state pipeline</li>
  <li>Write S3WAAS state data acquisition pipeline, data mapper,</li>
  <li>Test S3WAAS state pipeline</li>
  <li>There are no conflicts with respect to start sequence</li>
</ul>
<!-- <p style="font-size:20px">1.IGOD state pipeline</p>
<p style="font-size:20px">2.IGOD state data acquisition task, data mapper task</p>
<p style="font-size:20px">3. Prototyping ongoing for a generic data store pipeline using</p>
<p style="font-size:20px">4.topics and kafka connect</p>
<p style="font-size:20px">Next</p>
<p style="font-size:20px">5. S3WAAS state pipeline</p>
<p style="font-size:20px">6.Write S3WAAS state data acquisition pipeline, data mapper,</p>
<p style="font-size:20px">7. Test S3WAAS state pipeline and IGOD state pipeline and see</p>
<p style="font-size:20px">8. There are no conflicts with respect to start sequence</p> -->

# 
<p style="font-size:40px;color:orangered;">Devops Activities being so far</p> 
<p style="font-size:20px">Activities</p>
<ul style="font-size:20px">
  <li>HW requirements shared</li>
  <li>DB Prototyping</li>
  <li>A mock data set of 1 lac records created</li>
  <li>Testing ongoing in postgres for:</li>
  <li>Facet search</li>
  <li>Partitioning(horizontal and vertical)</li>
  <li>Free text search</li>
  <li>Field level access control</li>
</ul>

#
<p style="font-size:40px;color:orangered;">Milestone 1 Items Summary..1/2</p>
<table style="font-size:20px">
<tr>
  <td>Item</td>
  <td>Status</td>
  <td>Remarks</td>
</tr>
<tr>
  <td>Requirements Gathering</td>
  <td>Ongoing</td>
  <td>SRS/Data Analysis/Architecture</td>
</tr>
<tr>
  <td>UI Mockups</td>
  <td>Ongoing</td>
  <td>Need to converge on UI landing page and navigation</td>
</tr>
<tr>
  <td>Data Acquisition Framework and Pipeline</td>
  <td>Ongoing</td>
  <td></td>
</tr>
<tr>
  <td>Authentication System and API GW</td>
  <td>Not Started</td>
  <td></td>
</tr>
<tr>
  <td>CMS setup</td>
  <td>Ongoing</td>
  <td></td>
</tr>
<tr>
  <td>Infra Setup</td>
  <td>Not Started</td>
  <td></td>
</tr>
<tr>
  <td>Datastore setup</td>
  <td>Not Started</td>
  <td></td>
</tr>
<tr>
  <td>Prototype Demonstration</td>
  <td>Ongoing </td>
  <td>Would need a use case that stakeholders would like to see</td>
</tr>
</table>

# 
<p style="font-size:40px;color:orangered;">Milestone 1 Items Summary..2/2</p>
<table style="font-size:20px" >
<tr>
  <td>Item</td>
  <td>Status</td>
  <td>Remarks</td>
</tr>
<tr>
  <td>Project Management</td>
  <td>Ongoing</td>
  <td></td>
</tr>
<tr>
  <td>Documentation</td>
  <td>Ongoing</td>
  <td></td>
</tr>
</table> 

#
<div style="display:flex;width:100%;height:100%;border:4px solid orangered">
  <div style="width:50%;height:700px;align-item:center;padding-top:32%;font-size:40px"><h3 style="color:orangered">Current Project Team Organization</h3></div><div style="width:50%;height:700px;background-color:teal;align-item:center;padding-top:35%;"> <p style="font-size:15px">Team Composition</p> </div>
</div>

# 
<p style="font-size:40px;color:orangered">Team Composition</p>
<table style="font-size:20px" >
<tr>
  <td>Role</td>
  <td>K&A</td>
  <td>NIC Contact</td>
</tr>
<tr>
  <td>Program Manager</td>
  <td>Nitu Gupta</td>
  <td>Lokesh Sir</td>
</tr>
<tr>
  <td>Project Manager</td>
  <td>Monika Verma</td>
  <td>Lokesh Sir/Pankaj</td>
</tr>
<tr>
  <td>Development Lead</td>
  <td>Varad Gupta</td>
  <td></td>
</tr>
<tr>
  <td>FrontEnd</td>
  <td>Deepak NegiFarhan</td>
  <td></td>
</tr>
<tr>
  <td>BackEnd Team</td>
  <td>Adarsh/Verma/Barsha/Jai</td>
  <td></td>
</tr>
<tr>
  <td>DevOps Team</td>
  <td>Neeraj Yadav/Paul</td>
  <td></td>
</tr>
<tr>
  <td>CMS Lead</td>
  <td>Manoj Mahanta</td>
  <td></td>
</tr>
<tr>
  <td>Documentation Lead</td>
  <td>Monika Verma</td>
  <td></td>
</tr>
<tr>
  <td>Test Lead</td>
  <td>Kapil Jain</td>
  <td></td>
</tr>
</table> 

# 
<p style="font-size:40px;color:orangered">Project Organization Structure</p>
<img src="30.png" style="border:10px solid orangered">

# 
<div style="display:flex;width:100%;height:100%;border:4px solid orangered">
  <div style="width:50%;height:700px;align-item:center;padding-top:32%;font-size:40px"><h2 style="color:orangered" >Thank you</h2></div><div style="width:50%;height:700px;background-color:teal;align-item:center;padding-top:35%;"></div>
</div>