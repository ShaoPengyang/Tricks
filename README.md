# Tricks
##### FairGo results -> nan in BPR Loss.  log(sigmoid(r(ui)-r(uj))), sigmoid(r(ui)-r(uj))->0
##### Log supports > 0, if balancing parameter is big, r(ui)-r(uj) can be very low. sigmoid(r(ui)-r(uj))->0 log -> nan

##### Fair RANKING: FROM THE ITEM SIDE
