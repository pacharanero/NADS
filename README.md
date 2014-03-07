NADS
====

National Ambulance Standards for Documentation - NADS
This repo contains partially completed clinical modelling of the RCP National Ambulance Documatation Standard.

LICENSE
=======

The original work is not yet completed or released to the public, however since it is likely to be published soon and the intention is that it will be free and open access using the extremely permissive OGL, I have licensed this derivative work here under the GPLv3 in an effort to ensure some copyleft for the community.

IT suppliers then have the choice of using the raw work, with permissive OGL license (but it is not detailed enough to implement as it is and will require significant specialised clinical modelling to make workable), or this work which (when complete) will be detailed enough to directly implement in code - BUT you have to share back any improvements to the community! C'est la vie!

FILES
=====

* LICENSE - GPLv3 (see above)

* openEHR-EHR-ADMIN_ENTRY.ambulance_incident.v1.adl
  * this is an openEHR archetype. It can be opened in a text editor (if you have a strong enough stomach and just LOVE curly brackets). There is a GUI editor (Windows only) here: http://www.openehr.org/downloads/archetypeeditor/home
  * It's an open standard (www.openehr.org). 
  * This particular archetype covers just the parts of the NADS standard relating to the ADMINISTRATIVE parts of the ambulance incident, not the clinical bits. (Call out times, etc)
  * archetypes already exist for demographic details, staff details, medications, and problem/diagnosis - so these can be drawn on when building a template which would combine the incident details archetype with all those others to define the full NADS standard.

* README.md - is this that you're reading now

* National Ambulance Documentation Standard_Final headings.pdf is the standard from which I have developed these archetypes. I'm jumping the gun in putting it on here but I think it's unlikely that the RCP get on GitHub that much these days. (reminds me of a joke: how do you hide a fiver from an orthpaedic surgeon? put it in the patient's notes)

* NADS - National Ambulance Documentation Standards Consultation Mindmap based on .docx version 0.3 late Jan 2014.xmind
  * this is a mindmap of the whole standard showing all the nodes (=sections) and leaves (=data fields). Xmind is free and open source, crossplatform and awesome. http://www.xmind.net/
