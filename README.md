# bnlearn
:exclamation: This is an experimental, modified version of bnlearn (https://www.bnlearn.com/). Unless you are specifically looking for this version of the package, I strongly discourage its use due to very likely crashes.

This version is specifically tailored to bypass almost all the necessary security checks that bnlearn uses when adding arcs to a network, scoring a network and creating an empty graph. It serves the purpose of greatly speeding up the execution time of structure learning algorithms that want to evaluate the BIC or simmilar scores of a network and they know beforehand that this network is a valid DAG.

Unless the user is specifically searching for this modified version, I advise strongly against its use. The modifications made are ad-hoc and don't take into consideration ANY compatibility uses. Its only purpose is to speed up the Gaussian BIC score and generating networks from empty graphs. Using this version as a regular bnlearn distribution will probably result in unexpected behaviour.
