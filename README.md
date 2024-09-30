# TSTriggers
Database triggers have been introduced since the 1980s and their
value has been widely recognized allowing to automate tasks and
enforce business rules at the database level, ensuring data integrity,
auditing, and consistent logic across applications. They allow for
event-driven automation and real-time processing. However, notwithstanding their high value, the use of triggers in mainstream triple
stores has been mostly overlooked, despite the fact that online KGs
such as DBpedia and WikiData are rapidly updated and that there
are several scenarios where KGs must respond quickly to changes.
Current solutions typically rely on the application layer, which
continuously monitors the incoming data and applies the necessary updates. In this work, we propose a novel solution relying
on a new interpreted language that, coupled with an integrated
development environment (IDE) and graphical user interface (GUI),
introduces triggers to transform triple store-based KGs into reactive,
self-correcting entities
