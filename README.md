Language used: Java

# M/M/1 Simulation
An M/M/1 queue is a stochastic process whose state space is the set {0,1,2,3,...} where the value corresponds to the number of customers in the system, including any currently in service.

Arrivals occur at rate λ according to a Poisson process and move the process from state i to i + 1.
Service times have an exponential distribution with rate parameter μ in the M/M/1 queue, where 1/μ is the mean service time.
A single server serves customers one at a time from the front of the queue, according to a first-come, first-served discipline. When the service is complete the customer leaves the queue and the number of customers in the system reduces by one.
The buffer is of infinite size, so there is no limit on the number of customers it can contain.


# M/D/1 Simulation
An M/D/1 queue is a stochastic process whose state space is the set {0,1,2,3,...} where the value corresponds to the number of entities in the system, including any currently in service.

Arrivals occur at rate λ according to a Poisson process and move the process from state i to i + 1.
Service times are deterministic time D (serving at rate μ = 1/D).
A single server serves entities one at a time from the front of the queue, according to a first-come, first-served discipline. When the service is complete the entity leaves the queue and the number of entities in the system reduces by one.
The buffer is of infinite size, so there is no limit on the number of entities it can contain.


# M/M/c Simulation
An M/M/c queue is a stochastic process whose state space is the set {0, 1, 2, 3, ...} where the value corresponds to the number of customers in the system, including any currently in service.

Arrivals occur at rate λ according to a Poisson process and move the process from state i to i+1.
Service times have an exponential distribution with parameter μ. If there are fewer than c jobs, some of the servers will be idle. If there are more than c jobs, the jobs queue in a buffer.
The buffer is of infinite size, so there is no limit on the number of customers it can contain.
