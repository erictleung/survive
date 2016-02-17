# Basic Definitions

- **survival analysis** - the statistical analysis and modeling of time-to-event
  data taking into account censored data
    - Note: before advent of survival analysis, incomplete data were thrown
      away, which may have useful information, and introduce systematic bias
- **time-to-event data** - times series data until one or more events happen
- **censored data** - data on individuals or products for failure that are not
  observed
- **failures** - the time of a particular event of interest e.g. death,
  mechanical failure
- **probability density function** (p.d.f.) - a function that describes the
  likelihood for this random variable to take a given value e.g. normal
  distribution
- **cumulative distribution function** (c.d.f.) - the cumulative area
  underneath the probability density function from `0` to some `t`

  ![Cumulative distribution function](images/cdf.png)

- **survival function** (or reliability function) - the probability that an
  individual survives up to a time `t`

  ![Survival function](images/survival.png)

    - Alternate definition - "...property of any random variable that maps a
      set of events, usually associated with mortality or failure of some
      system, onto time" Source: [Wikipedia][survival]

- **harzard function** (or risk or mortality rate)- instantaneous failure rate

  ![Hazard function](images/hazard.png)

- **Censoring models**
    - **Type I censoring**
    - **Type II censoring**
    - **Random censoring**
        - **Right censoring**
        - **Left censoring**
        - **Doubly censored**
    - **Interval censoring**
    - **Truncation**

[survival]: https://en.wikipedia.org/wiki/Survival_function
