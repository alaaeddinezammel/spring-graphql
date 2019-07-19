# spring-graphql
poc: spring boot + graphql
just hit run as spring boot application

& and put this url in the browser 
http://localhost:8055/graphiql

and enjoy testing api 

for example 
{
countApplications
 }
*************************OR***********************

{
findAllApplications{
  
  id
  owner
  
  description
}
  
 }

*************************OR***********************
{
findAllApplications{
  
  id
  owner
}
  
 }
 
.
.
.
etc
