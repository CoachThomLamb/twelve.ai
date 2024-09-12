### Service Finder - Functional Spec

*Drafted by:* Thomas Lamb, Sept 12, 2024

## Definitions 

**Member** A member of AA. 

**Profiles** A record created by a member to encapsulate the information required to identify appropriate Service Positions they may want to apply for. 

**Service History** A record of the previous service positions held by the member. (optional)

**Groups, Service Boards or Committees (GSBC)** Tradition 9. AA does not have organization, so we want to ensure that the Service Finder respects that and allows for the creation of a service position that serves a Group directly or a Service Board or a Committee. 

**Service Position** Any position at any level that can be filled by a member of AA and serves AA. 

**Admin** The name of the Account type a Group, Service Board or Committee can use to create and manage their  available Service Positions. 

## Functions 

1. Members can create Profiles. 
2. Admins can create Service Position Listings. 
3. Members can search for Service Position Listings using filters and a text input for search terms. 
4. Members can request outbound notifications (email, text message, in app notificaion) for new service positions that match a set of criteria they define. 
5. Members can apply to a Service Position or request more information. 
6. Admins can create a Service Position Listing and define a set of member attributes that are suggested for the position. 
7. Admins recieve outbound notifications(email, text message, in app notification) when Members inquire about one of the Admins listings. This can be on event or at a routine interval (implementation detail). 
8. 

## Filter types
1. Group, Service Board or Committee Type;
2. Geographic; 
3. Role type;
4. Member Attributes *(requirements, eg: how much sobriety, has a car etc)*;
5. Events;
6. Key words; 
7. search terms. 

## Anonymity options
The profile could obfuscate the Personal Identifying Information of the member if that is useful. The Member would be free to label their profile with whatever identifier they want, and their email could be obfuscated as well. These are options. 

