# Sources for University of California, Berkeley and UNIX

- ["EO-OUEL: A System for the Manipulation and Display of Geographic Data"](https://dl.acm.org/doi/10.1145/563858.563892) \
  Richard R. Berman and Michael Stonebraker \
  Department of Electrical Engineering and Computer Sciences,
  University of California, Berkeley \
  SIGGRAPH '77, 20 July 1977

  > We turn now to the performance comparison. […] These commands were made with
  > no other activity present on our PDP-11/70 system. Note that this penalty is
  > only a factor of 2-4. The authors feel that this penalty is an upper bound
  > on the penalty of our "front end" approach. Moreover, a large part of the
  > penalty is probably accounted for by the fact that INGRES must run as
  > multiple processes [8] because of its size. This necessitates passing
  > commands and data between processes through the UNIX interprocess
  > communications facility [13]. Since the mock-up runs as a single process it
  > incurs no communication overhead. However, a real special purpose system
  > would be much larger than the mock-up and would necessitate at least some
  > communication overhead.
  >
  > In summary, the authors feel that a factor of 30-40 in software development
  > costs in exchange for a factor of 2-4 in performance is often an
  > advantageous exchange. Further- more, given the trends in hardware and
  > software costs, this exchange should become even more beneficial in the
  > future.
