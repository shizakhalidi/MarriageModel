# MarriageModel
Credits to Dr Shah Jamal for creating the outline:
The model was designed to simulate monogamous marriages and to address
the following question: How does variability in the life expectancy, marriage-age, and
female-to-male ratio affect the rates of monogamous marriages in a population?

Agents/Entities and Time:
a. Agents/Entities: We have one kind of entity: individuals representing humans in a
society. Agents are characterized by the following attributes:
i. Gender: Either ‘male’ or ‘female’.
ii. Age: specified in years, ranging from 1 to max-age. The default is 80 years.
iii. Marital status: At any time, agents are either ‘unmarried’, ‘married’, or
‘widowed’. At the time an agent is created, they are assigned the
‘unmarried’ marital status.
iv. Spouse: an agent with whom a marriage link is established. In that case,
both the agent and their spouse’s marital status is set to ‘married’. [Hint: use
nobody primitive in NetLogo for a spouse when a spouse does not exist –
check dictionary].
b. Time: A tick (time step) in this model corresponds to one year in the lifetime of
agents.
