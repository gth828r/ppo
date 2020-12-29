# Introduction
This repository contains an implementation of PPO. Initially the plan was to
explore how CQL affects PPO, but with a deeper understanding of both PPO and
CQL, it appears to make more sense to explore CQL applied to the soft actor
critic algorithm. The primary reason is that PPO's design was not specifically
for offline RL, while SAC's is designed for offline RL. CQL is specifically a
tool to use for helping generalize with offline RL.

See https://github.com/gth828r/sac-cql for exploration of CQL applied to SAC.
