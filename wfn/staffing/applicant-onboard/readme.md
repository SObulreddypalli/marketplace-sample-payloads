
# **Applicant Onboard - ADP Workforce Now**

## ADP Workforce Now® (ADP WFN) allows client practitioners to add new employees using the New Hire Template.  The Applicant Onboard Event Application Programming Interface (API) posts an applicant into ADP WFN using a template as an In-Progress Hire.

### A complete API Guide is available at the following link given below:
#### [Applicant Onboard WFN Guide](https://developers.adp.com/services/elasticsearch/articles/guides/82f633cbebcb730a22c4973082ed29542ed3bebc/doc/ApplicantOnboardAPIGuide-ADPWorkforceNow.pdf)

#### The requests and responses for each api are categorized into two folders:

1. success
2. errors

#### The success folder contains requests and responses which result in http status codes as 200 and 201. These mostly include: 

1. Meta Responses
2. Codelist responses
3. All possible success calls for the api.

#### *Note: For the GET calls requests have not been included.*

#### The error folder contains requests and responses which result in http status codes as 400 and 404. These mostly include scenarios where: 

1. Mandatory fields are not sent in the request
2. Incorrect values are sent for mandatory fields in the request.


