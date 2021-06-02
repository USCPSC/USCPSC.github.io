


 <img src="https://www.cpsc.gov/sites/all/themes/cpsc/images/logo.png" alt="CPSc Logo" width=52 height=52> 
 

 
## Saferproducts.gov   

Located at www.saferproducts.gov, the portal allows the public to search for and review reports on consumer products, as well as the comments that manufacturers or private labelers provide in response to those reports.

The incident management system is composed of a public portal, a data syncer, a business portal and an incident management application where business processes and  rules are applied to the incident reports before they are published to the public portal to be searchable.

#### Physical Architecture
<hr>


<img src="./Saferproducts.png" alt="diagram"  > 


### Technologies Used

#### saferproducts.gov
<hr>

<table>
 <tr>
 <th>Applications</th>
 <th>saferproducts (public)</th>
 
 <th>saferproducts (business portal)</th>
 <th>CPSC 360/ Incident Management</th>
  <th>saferproducts (search)</th>
 </tr>
 <tr>
  <td>Front End UI</td>
  <td>ASP.net Core 3.x, Jquery,Bootstrap CSS, HTML 5</td>
  <td>ASP.net Framework 4.0, Jquery,DevXpress</td>
  <td>ASP.net Framework 4.0, Jquery,DevXPress</td>
  <td>ASP.net Core 3.x, Jquery,Bootstrap CSS, HTML 5</td>
 </tr>
 <tr>
  <td>Form Validation</td>
   <td>Server Side C#, Jquery, HTML 5</td>
  <td>Server Side C#, Jquery & DevXpress </td>
  <td>Server Side C#, Jquery,DevXpress</td>
 <td>n/a</td>
 </tr>
 <tr>
 <td>Business Logic Layer</td>
  <td>.Net Core 3.x</td>
  <td>.Net Framework</td>
  <td>.Net Framework</td>
  <td>.Net Core 3.x</td>
 </tr>
 <tr>
  <td>Data Access Layer</td>
   <td>Dapper, MS Entity Framework</td>
  <td>Custom ORM</td>
  <td>Custom ORM</td>
  <td>Dapper, MS Entity Framework</td>
 </tr>
 <tr>
   <td>Database</td>
   <td>Sql Server</td>
  <td>Sql Server</td>
  <td>Sql Server</td>
  <td>Sql Server,Elasticsearch</td>
 </tr>
</table>

Packages & Versions
<hr>

.NET Core Core 3.x 

ASP.NET Core 3.x Razor pages 

Entity Frame Core 3.1.4 

Dapper 2.0.35 

Google reCAPTCHA v2 (I am not a robot) 

MailKit 2.6.0 

SQL Server 2012 R2 

Bootstrap/CSS/jQuery 

IronPdf (2020.0.0) 

Elasticsearch.Net 7.8.1 

NEST 7.7.1 

Log4net 3.1.0 

JDK 1.8.0 (needed for the Elasticsearch Engine) 







