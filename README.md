
###                              Ownership at Large
###                  Open Problems and Challenges in Ownership Management


#### Summary

Authurs:
JohnAhlgren  ,Maria Eugenia Berezin, Kinga Bojarczuk, Elena Dulskyte ,Inna Dvortsova ,Johann   George, Natalija Gucevska, Mark Harman, ShanHe, Ralf Lämmel, ErikMeijer, Silvia Sapora, and Justin Spahr -Summers∗ FacebookInc.

Conference :
This paper appears in Proceedings of 28th International Conference on Program Comprehension,ICPC2020.

INTRODUCTION :  Managing software asset ownership in any organization is important.In this paper, when we refer to 'asset' we include entities as diverse as source-code files, tables in the data warehouse, and software configurations. When we refer to the 'owner' of an asset, we mean this term in a broad sense: a set of people who take responsibility for the asset. Standard processes, e.g., based on escalation, are typically in place to rule out unowned assets, as they would clearly be a cause for concern. A more nuanced question is the one of 'ownership health', i.e., whether each asset is attributed to the 'most suitable' owner.Who is the most suitable owner of a given asset changes over time, e.g., due to reorganization and individual function changes. Attributing assets to owners and measuring ownership health encompasses a combination of static and dynamic properties of the software assets themselves, the workflows for developing and managing the assets, and the structures of the organization that possesses the assets.
Methodology : 2.1 Vocabulary of Ownership Management The term resource alludes to such an element that is a piece of a framework or is controlled by an organization of intrigue.Accept an extraordinary piece of a framework: its resource for proprietor attribution planning or just attribution, which maps advantages for proprietor competitors, which are in this way alluded to as proprietors.The dark bolts on the left express that the resource for proprietor attribution planning is mostly encoded in the benefits themselves, for example, by explanation inside documents or a metastore for tables, in which case extraction can be applied to resources or conceivably to logs that record the proprietors 'in real life'. 
The quantity of oncall turns is under 10k. Number of proprietor possibility for a given resource a. It is frequently conceivable, subject to heuristics dependent on key highlights, to limit to a short rundown of proprietor applicants that are at all conceivable for the benefit an and that should be positioned in this manner. 
The day by day stir for source-code documents in one of the greater mono repos of Facebook is around 100k. Every day proprietor beat for resource type t. Such stir is important as heuristics/ML should computerize these changes. 
For a significant resource type for planned pipelines in the information distribution center with about 100k resources, the totaled day by day proprietor beat in the course of the most recent 4 months is about 10k while there were a few days with a few several influenced resources - this 
