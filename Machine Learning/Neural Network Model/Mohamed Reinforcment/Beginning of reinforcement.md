A **state** ![s](https://spinningup.openai.com/en/latest/_images/math/96ac51b9afe79581e48f2f3f0ad3faa0f4402cc7.svg) is a complete description of the state of the world. There is no information about the world which is hidden from the state. An **observation** ![o](https://spinningup.openai.com/en/latest/_images/math/ca2d5053d03bd8fd9f399e5afbb834202e2d2f2d.svg) is a partial description of a state, which may omit information.
Different environments allow different kinds of actions. The set of all valid actions in a given environment is often called the **action space**.
Different environments allow different kinds of actions. The set of all valid actions in a given environment is often called the **action space**.
A **policy** is a rule used by an agent to decide what actions to take. It can be deterministic, in which case it is usually denoted by ![\mu](https://spinningup.openai.com/en/latest/_images/math/123eb57279cfbea38a65e8e129bda64972fedc3d.svg):![a_t \sim \pi(\cdot | s_t).](https://spinningup.openai.com/en/latest/_images/math/89757355805c4084ac93610e9581c060f2e61610.svg)
there are two types of policies
Deterministic 