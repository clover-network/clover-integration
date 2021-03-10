## Integration with the Graph

* Provide one or more URL's for ethereum clients
    > https://rpc-3.clover.finance/
    * Are the clients archive nodes?
      >No, It's a full node
    * Do the clients support the Parity tracing API? (Geth tracing is
      currently not supported)
      > No
    * Who can we contact if there are issues with those ethereum clients?
      > yiqun and pangwa in the clover-graph channel

* What should the chain be called in subgraph manifests, i.e., what do
  users put for `network: <name>` into their manifests?
  > clover

* Provide a list of email addresses that should get access to the staging
  environment
  > yiqun@clover.finance
  >
  > pangwa@gmail.com
* Do you have test subgraphs that can be deployed? We will ask you to
  deploy one or several test subgraphs in the staging environment, and,
  once they are syncing, to verify that the results are what is expected.
  > No, we don't have any experience with subgraphs before.

* When the chain is enabled in production, do you anticipate any subgraphs
  with high query volumes (more than 2M requests/day) to be deployed? If
  so, which ones? How can we contact the people maintaining those
  subgraphs?
  > The production launch date is TBD. At the beginning, we don't think we need that high query volumes. 
  > As the query increase rapidly, we will need subgraphs with high query volumes deployed, and will contact you.