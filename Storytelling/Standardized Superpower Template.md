
# Standardized Superpower Templates
This template considers a "Superpower" to be a form of superhuman ability that is innately a part of the user once acquired. It is not a magical talent, and it is either passively available at all times or activated more or less by intention. The specifics mechanics of each superpower may vary, but there are few exceptions to these rules.

Some superpowers appear to defy the traditional laws of physics, such as altering the flow of time or moving faster than light speed. These can generally be explained as influencing matter at higher dimensions that cascades its effects into our realm.

Superpowers are assigned to logically similar groups rather than packed into one. For example, Superman would be described as possessing many superpowers, not one of them. His powers would include a very high combat classification of Laser Eyes, a mid-level utility classification of X-Ray Vision, and so forth.

## Advantages of Standardizing Storytelling Templates
* Creates a consistent format to train AI models on.
* Creates a consistent format for editors, APIs, databases, and other development tools to use.
* Enables simple and automatic integration into related storytelling materials.
* Greatly simplifies collaboration between storytellers.
* Greatly simplifies worldbuilding process and reduces the time investment.
* Provides a shared vocabulary and understanding among the community.
* Enables a universal system for lookup and retrieval.
* Simplifies the process of generating content for an AI.
* Allows storytellers to quickly and easily manage entire settings.
* Allows quick modification of existing content.


## The Superpower Template
The superpower template is a single markup file with specific heading requirements as part of the specification. Some primary headers also have secondary headers.

The designated headers within the template are as follows:
* SuperpowerID: A Global Unique Identifier that identifies the superpower within the globally shared library of superpowers.
* Utility Class: Indicates what utility class this power belongs to, or how useful it is. See 'Utility Class' notes.
* Combat Class: If the power is suited for combat, this indicates the approximate power level. See 'Combat Class' notes.
* Quality of Life Class: Indicates the approximate adjustment of the user's quality of life. See 'Quality of Life Class' notes.
* Build Instructions: An original text instruction preparing it for AI generation. AI should only read this text, never overwrite it.
* Abilities: Describes the advantages, disadvantages, mechanics, effects, activation requirements, and other aspects of the power's abilities.
* Implicit Powers: Describes secondary powers that are acquired out of necessity to ensure the power's primary abilities work as intended.


#### Utility Class
Usefulness, for the purposes of defining the utility class, is rated by the reduction of time it takes someone to complete a desired objective by using the power. The greater the time reduced, and the more often the user can make use of that time reduction, the more useful the power is. In some cases, a utility power can also make something possible that would have otherwise been impossible, which is the most potent form of usefulness relative to its frequency of application.

* Trivial: The power is minimally useful at best, and only in uncommon situations.
* Modest: The power is minimally useful sometimes, or somewhat useful in uncommon situations.
* Meaningful: The power is minimally useful frequently, somewhat useful sometimes, or useful in uncommon situations.
* Helpful: The power is somewhat useful frequently, useful sometimes, or very useful in uncommon situations.
* Blessing: The power is useful frequently, very useful sometimes, or extremely useful in uncommon situations.
* Empowered: The power is very useful frequently, or extremely useful sometimes.
* Optimal: The power is extremely useful frequently.

#### Combat Class
All of the combat class descriptions assume that unpowered opponents have no superpowers and has no access to special technology that would effectively recreate a superpower during the battle. The term "consistently" refers to a 90% statistical success rate or better.

* Minor Class: Indicates the power may only have a limited, often trivial effect on combat.
* Solo Class: Indicates the power would consistently enable the user to win a typical one-on-one fight with an unpowered opponent.
* Fighter Class: Indicates the power would consistently enable the user to win a fight against a handful of unpowered opponents.
* Street Class: Indicates the power would consistently elevate someone to being capable of fighting every unpowered opponent on a local street, even when coordinated.
* City Class: Indicates that someone with this power will consistently defeat any number of unpowered opponents, even the highly coordinated and specially equipped.
* World Class: Indicates that this power will consistently defeat any unpowered threat the world could muster.
* Hero Class: Indicates the power would consistently elevate someone to beat an opponent with a World Class superpower.
* Super Class: Indicates a power that is more or less a cheat code to victory.

#### Quality of Life Class

* Undesired: This power is more of a burden than its advantages are worth.
* Trivial: Though the power doesn't improve life much, it doesn't have any significant drawbacks.
* Modest: The power brings a reasonable amount of pleasure or simplicity that is worth any drawbacks it might have.
* Beneficial: The power is so beneficial that the user's quality of life would noticeably decrease if it were lost.
* Significant: The power upgrade the user's quality of life by a substantial amount. Losing it could be devestating.
