DC Core integration/staging tree
=====================================

http://www.dcpass.io

What is DC PASS?
----------------

DC is a kind of protocol token, which is also a bifurcated currency of YF series. It aims to solve the overall planning problem of YF series currency. 
YF series currency is the currency that can be circulated on swap through user collection and can be used for mining. However, 
it is difficult to distinguish the authenticity of all YF series coins. How to make miners accurately find YF series coins, 
how to combine all YF series coins, and how to connect all YF series coins with each other, 
DC is what DC wants to do. DC can not only coordinate YF tokens, 
but also motivate users through various algorithms (workload proof). In short, 
if you have enough YF tokens and enough transaction volume, the more YF agreement rewards you can get.

For more information, as well as an immediately useable, binary version of
the DC Core software, see http://www.dcpass.io

License
-------

DC Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md).

Developer IRC can be found on Freenode at #DC-core-dev.

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test on short notice. Please be patient and help out by testing
other people's pull requests, and remember this is a security-critical project where any mistake might cost people
lots of money.

Testnet is now up and running and available to use during development. There is an issue when connecting to the testnet that requires the use of the -maxtipage parameter in order to connect to the test network initially. After the initial launch the -maxtipage parameter is not required.

Use this command to initially start DCd on the testnet. <code>./DCd -testnet -maxtipage=259200</code>

### Automated Testing

Developers are strongly encouraged to write [unit tests](src/test/README.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`. Further details on running
and extending unit tests can be found in [/src/test/README.md](/src/test/README.md).

There are also [regression and integration tests](/test), written
in Python, that are run automatically on the build server.
These tests can be run (if the [test dependencies](/test) are installed) with: `test/functional/test_runner.py`


### Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.


About DC
----------------
A digital peer to peer network for the facilitation of asset transfer.



In the fictional world of Westeros, DCs are used as messengers who carry statements of truth. DC is a use case specific blockchain designed to carry statements of truth about who owns what assets. 



Thank you to the Bitcoin developers. 

The DC project is launched based on the hard work and continuous effort of over 400 Bitcoin developers who made over 14,000 commits over the life to date of the Bitcoin project. We are eternally grateful to you for your efforts and diligence in making a secure network and for their support of free and open source software development.  The DC experiment is made on the foundation you built.
