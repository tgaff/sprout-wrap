# VR Readme

  Roe is a workstation spin-up tool based on the previous oceans tools (deleted) and pivotal-sprout.  
  It is intended to make spinning up a fresh developer workstation with the components needed for Oceans and Neptune and friends easy.


## Maintenace

  As alluded to above, vr_master should be rebased on upstream_master periodically.  OSX changes often as do all the tools this ties together.
  We're leveraging the community to maintain all of the recipes so we don't have to.  
  
  Try to keep changes in vr_master to be primarily configurational - enabling or disabling required recipes and settings.  That should 
  help to minimize the rebase pain.

## History:

  Long, long ago in the early days and not-quite-so-early days of Oceans we could easily setup developer workstations.  Eventually the 
  tools that allowed this though suffered from lack of maintenance and the Oceans kingdom was plunged into an era of darkness in which
  each new developer tried to divine the truth of the workstation from the decaying scrolls of the developer wiki.  There was great 
  sadness upon the repo.  The tools had become non-functional and in a blaze of fire were 
  [purged](https://github.com/VerticalResponse/Oceans/commit/6e689c1248e76169bb4ef1dd5a016b2d33c4b0e7).

  Now these tools are revived and based on upstream open-source projects in the hopes that they may bring new light to the Oceans world.


### Why is this not README.md ?

  To make re-basing against [sprout-wrap](https://github.com/pivotal-sprout/sprout-wrap) easier.

### Why is there no master ?
  
  To force you to think twice and read this.
  There are two masters:
  
  * upstream_master - sync with upstream sprout-wrap to maintain latest updates
  * vr_master       - rebase on upstream_master with VR specific alterations


