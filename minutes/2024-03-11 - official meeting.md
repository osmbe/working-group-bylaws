# 2024 03 11: Official OSM BE members meeting

## Participants (14/30)

1. Jonathan Beliën
2. Joost Schouppe
3. Thierry Jiménez
4. Seppe Santens
5. Steven Clays
6. Thibault Molleman
7. Johan Joubert
8. Julien Minet
9. Ben Abelshausen
10. Erik Beerten
11. Johan Joubert
12. Pierre Parmentier

Apologized: Jorieke Vyncke, MD, Marc Gemis, Kurt Roeckx, Kevin Baker, Michaël Dierick, Pieter Vandecasteele

Votes by proxy:
- Tim Couwelier > Thibault Molleman
- Pieter Vander Vennet > Joost Schouppe

Meeting quorum: 1/4 (8 participants)
Voting: simple majority

## Location

[meeting-link](https://osmvideo.cloud68.co/user/joo-ua3-evt)

## Official Agenda

- retain public membership list?
  - Pros & cons were discussed. 
  - Current policy: required info is real name, address & town; osm username NOT required. Public info: real name, town.

Motion: only the total members and displaying only those who opt-in?[^1]
Votes against? 0
Votes in favor: 10 (including proxies)

We will have to rewrite the bylaws to implement this proposal, within a year or so, and deposit it to the national register.

    

## Update about the new organization

The troubles at our umbrella organization Open Knowledge Belgium VZW, made us decide to leave the organisation. This was formalized in July 2023. Funds were transferred temporarily to OSgeo vzw. The kindly hosted us for the rest of the year, so we could keep organizing the State of the Map Europe event.

By December 2023 the new non-profit OpenStreetMap Belgium vzw/asbl was registered. We were recognized as a Local Chapter of the OpenStreetMap Foundation by January 2024.

One of the larger tasks was to rewrite our [simple bylaws](https://github.com/osmbe/working-group-bylaws/blob/master/CONSTITUTION.md) to something that follows the law for Belgian non-profits. Some of the changes:
- formal automatic termination of membership (after two missed meetings)
- formalize existing procedures (e.g. registering as a member, corporate membership)
- obligatory registration of address of members

Links
* [bylaws](https://github.com/osmbe/working-group-bylaws/blob/master/CONSTITUTION.md)
* OKBE exit: [most detailed account](https://community.openstreetmap.org/t/osmf-local-chapter-re-application-osm-belgium/107234/5)

Pending:
* Local chapter document signing ([article](https://blog.openstreetmap.org/2024/02/14/welcome-openstreetmap-belgium-the-newest-and-returning-osmf-local-chapter/) ; [local chapters](https://osmfoundation.org/wiki/Local_Chapters))
* Finish setting up new bank account

### Summary of the last year

#### SOTM-eu
Some numbers:
![SOTM-EU-Factsheet_v2](https://hackmd.io/_uploads/H1mmrA266.jpg)
Nice event, good cooperation with TomTom, could not have happened without them, nice profit of +15K that will be transfered to SoTM Europe in Poland for the next conference.
Congrats to the organisers!

#### 2023 yearly report

[**Report**](https://hackmd.io/urW1TmoFSzuBiHlxsgA67w?view#Reboot-as-independent-organization)

- establishment of new bylaws and new vzw/asbl
- activity report
- financial report (excl. SOTM Europe); very limited income, because of all the trouble stated above.

**Discussion:**
* It would be good to have an agreement on how much the board can spend (for daily costs) and when they have to consult the membership (for bigger investements). It could be incorporated in the bylaws, but maybe that's not really necessary. Proposals are welcomed!
* How much of our funds should we actually spend? Proposals: 
    * attending events, e.g. with an official OSM.be booth.
    * "PR in general" (e.g. having a nice write-up or movie accompanying our key projects). For reference, see the attention we got from the street imagery story of Stephane in Brussels
* Is it still feasable to attract corporate members? It's probably not a problem, but it requires effort.

### Plans for 2024

#### Top mapping tasks
* https://wiki.openstreetmap.org/wiki/WikiProject_Belgium/top_mapping_tasks
* is it still up to date?
* what should we focus on in 2024? in the next years?

#### Resolving notes
* https://wiki.openstreetmap.org/wiki/WikiProject_Belgium/Resolving_notes
* Mikidi: When I last looked in to it, I concluded that https://ent8r.github.io/NotesReview/ gets pretty close to the best you can have without setting up a supplementary DB to find actionable notes. (although the initial setup is a little counter intuitive. See previous thread.)
We concluded that generally speaking, we are a little lax when it comes to closing notes when just not actionable. Some of the ones that only seem actionable in some future can be resolved with https://wiki.openstreetmap.org/wiki/Lifecycle_prefix
(as always), to make a bigger difference, stimulating community involvement is key. Many people indicated they would be up for another notes mapathon.

**Discussion:**
* It would be good to have a regular (virtual) meetup for closing notes
* There's a consensus that it's still important to focus on resolving the notes in Belgium
* Ben: Idea to research https://thegeomob.com/

#### OSM's 20th Birthday

[Should we and if so, how celebrate OSM’s 20th Birthday?](https://community.openstreetmap.org/t/how-should-we-celebrate-osms-20th-birthday/108542)
Also see https://wiki.openstreetmap.org/wiki/OpenStreetMap_20th_Anniversary_Birthday_party

Open proposal: we still organize the yearly bbq in the afternoon.
In the morning/noon we could organize a mini physical mapathon announcing the 20th Birthday and we can link it to some of our (open data) requirements as the new governments will be formed at that moment
Date: Saturday 6 July 2024 (anniversary is on 9th August)

It would be good to have a press release as well.

#### OSM.be free tile server
Geo-6 will no longer be updating the OSM.be free tile server (see [the list of sites that we know are using these tiles](https://wiki.openstreetmap.org/wiki/WikiProject_Belgium/Websites)). However, Champs-Libres has reached out to us, offering to take over this job. They already provide some freely accessible tiles at  https://tiles.champs-libres.be/ : an interactive version of the OpenArdennesMap and a version of CyclOSM. Both use the very detailed hillshade+contour lines that Champs-Libres generated a few years back.

The general idea is that we would migrate the existing OSM.be tiles (including the historical versions) to a new OSM.be-run server. The folks at Champs-Libres would take over the generation of the NL/FR/normal OSM.be styled tiles locally, and then push them to the OSM.be server. The tiles would then be updated about twice a year. They would also push the OpenArdennes & CyclOSM tiles there.
The server would be controlled by OSM.be, but daily management would be done by Champs-Libres.

One of the harder aspects of this process, is that we have the OSM.be style that was last forked from the main OSM.org style about four years ago. The changes have to do with language and some icons specific to Belgium. Champs-Libres would apply this changes to the current OSM.org style, and repeat that procedure every other year.

All of this is quite some work. Champs-Libres proposes to do this work in lieu of payment for their continued Corporate Membership. Considering the amount of work involved, this appears to be a good deal for OSM.be.

#### Matrix
* pay supporting [membership fee](https://matrix.org/membership/) to Matrix: 60€ per year for individuals ; 2000+€ for organizations ([FOSDEM presentation](https://fosdem.org/2024/events/attachments/fosdem-2024-3345-opening-up-communication-silos-with-matrix-2-0-and-the-eu-digital-markets-act/slides/22568/2024-02-04_FOSDEM_DMA_with_Matrix_2_0_f7oic1B.))





[^1]: https://github.com/jbelien/mailchimp-osm/issues/126