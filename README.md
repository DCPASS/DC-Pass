DC Core integration/staging tree
=====================================

http://www.dcpass.io

What is DC PASS?
----------------

Introduction to Dragonfly cold wallet DC token:

The independent monetary and financial system of defi brings the dawn of Inclusive Finance. Libra has set off a wave of Inclusive Finance, but Inclusive Finance is not only to provide basic financial services for the financial marginal groups; it is also an important part of Inclusive Finance to provide better financial products for the large-scale middle class, bottom workers and other ordinary investment groups with limited funds. Dragonfly wallet DC is positioned to serve ordinary investors all over the world, so that they can enjoy the high-quality investment products usually enjoyed by the high net worth group, enjoy the equal wealth growth power with the high net worth group, and enable the investors even far away from China to enjoy the high-quality financial services in the UK. Based on the advantages of existing resources, dragonfly token DC is committed to attracting institutional financial service providers to join Dragonfly wallet DC inclusive financial infrastructure alliance by taking advantage of the advantages of existing resources, decentralized financial technology, low-cost cross-border circulation of capital, openness and transparency, so as to create a new generation of institutional inclusive financial infrastructure, meet the "needs" of ordinary investors and help them realize their investment“ The benefits of "freedom" are stable and safe. Dragonfly token DC provides a safe, convenient and decentralized one-stop management scheme by supporting a variety of blockchain asset types. Users can use Dragonfly wallet to store, manage and exchange the mainstream digital currencies such as usdt and wave field, which can not only fully control their own digital assets, but also greatly reduce the use threshold and management burden of digital currency, and effectively promote the flexible application of digital assets.



DC economic model of dragonfly wallet token

The digital asset issued by DC project is Dragonfly coin, referred to as DC, which is based on wave field trc20 protocol, with a circulation of 380000 pieces. DC Dragonfly coins are distributed completely through decentralized mining. The only way for users to obtain DC Dragonfly coins is to pledge mining DC institutional investment product quota by locking TRX and various token stable coins, so as to dig out DC, and ordinary investors have the opportunity to participate. In addition, holding DC can also enjoy the rights and interests of voting on key issues and dividends.



Principal guaranteed financial management: DC capital guaranteed financial products provide real capital guaranteed financial management, and the principal invested by users is underwritten by Willis investment management insurance, a well-known British insurance company, which is a long-term strategic partner of DC. The insurance coverage includes: Investment Manager civil liability, fund civil liability, investment manager management liability and fund management As we all know, insurance companies are averse to high risk. Willis investment management insurance company has long provided risk protection for large investment products with good credit rating and low risk. It also proves the low risk and stable income of DC principal guaranteed financial products. According to the investors' different income and the preference of capital use period, DC principal guaranteed financial products will appear in the DC product matrix with floating yield and different maturities. Taking ARJ capital, a well-known diversified asset management service provider and private investment company in the UK, as an example, according to ARJ Based on the mature investment market experience, the monthly yield of DC's principal guaranteed financial products is expected to be around 30%, mainly depending on the rise of DC price

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
