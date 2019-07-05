
<!DOCTYPE>
<html>

<head>
	<title>Sprint Four: Build your own non-fungible Token
	</title>
</head>
<link rel="icon" href="Sawtooth.png" type="image/x-icon" />
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO"
    crossorigin="anonymous">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.0/animate.css">
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.2.0/css/all.css" integrity="sha384-hWVjflwFxL6sNzntih27bfxkr27PmbbK/iSvJ+a4+0owXq79v+lsFkW54bOGbiDQ"
    crossorigin="anonymous">
<link rel="stylesheet" type="text/css" href="style.css" />
<style>
	h2,
	h1 {
		font-weight: bold;
		text-transform: capitalize;
		color: black;
	}

	code {
		background: #335;
		padding: 5px;
	}

	a {
		color: #666;
	}
</style>

<body class='container'>
	<div class="main-content">
		<div>
			<div class="page">
				<h1 id="chatterbox-server">
					<strong>Sprint Four: Build your own non-fungible Token</strong>
				</h1>
				<hr>
				<br>
				<h2>Sprint Map</h2>
				<ul>
					<li>
						<a href="#Key-words">Key Words</a>
					</li>
					<li>
						<a href="#high-level-goals">High Level Goals of this Sprint</a>
					</li>
					<li>
						<a href="#getting-started">Getting Started and Project Set Up</a>
					</li>
					<li>
						<a href="#theproject">The Project</a>
					</li>
					<li>
						<a href="#extracredit">Extra Credit</a>
					</li>
				</ul>
				<br>

				<h2 id="Key-words">
					<strong>Key Words</strong>
				</h2>
				<hr>
				<ul>
					<li>smart contracts standards.</li>
					<li>non-fungible token.</li>
					<li>ERC721.</li>
					<li>ERC Ethereum request for comments</li>
					<li>Truffle.</li>
					<li>Solidity.</li>
					<li>Web3.</li>
					<li>Ethereum.</li>
					<li>CryptoKitties.</li>
					<li>smart contracts.</li>
				</ul>
			</div>


			<h2>What is the non-fungible token ??</h2>
			<p>A non-fungible token (NFT) is a special type of cryptographic token which represents something unique; non-fungible tokens
				are thus not interchangeable. This is in contrast to cryptocurrencies like Bitcoin, and many network or utility tokens
				that are fungible in nature.</p>

			<p>
				Non-fungible tokens are used to create verifiable digital scarcity. NFTs are used in several specific applications that require
				unique digital items like crypto-collectibles and crypto-gaming. Popular blockchain games like CryptoKitties make use
				of non-fungible tokens on the Ethereum blockchain NFTs are used to represent in-game assets, which are in control of
				the user instead of the game developer NFTs also find potential use in digital art, by helping prove authenticity and
				ownership
			</p>

			<p>
				The Ethereum community has adopted the ERC-721 protocol as a standard for Non-Fungible Tokens on Ethereum. Projects like
				CryptoKitties, CryptoPunks and Decentraland follow the ERC-721 protocol for their NFTs.
			</p>

			<p>
				Non-fungible tokens made their way into mainstream news when CryptoKitties went viral and subsequently raised a $12.5 million
				investment RareBits, a Non-Fungible Token marketplace and exchange raised a $6 million investment. Gamedex, a collectible
				cards game platform made possible by Non-Fungible Tokens raised a $800,000 seed round. The creation of the Non-Fungible
				Token protocol on the Ethereum blockchain has caused other blockchain projects such as NEO to begin development of their
				own non-fungible token standards.
			</p>
			<h2>What is ERC-721??</h2>
			<p>ERC-721 is a free, open standard that describes how to build non-fungible or unique tokens on the Ethereum blockchain.
				While most tokens are fungible (every token is the same as every other token), ERC-721 tokens are all unique. Think of
				them like rare, one-of-a-kind collectables.</p>

			<h4> THE STANDARD</h4>
			ERC-721 defines a minimum interface a smart contract must implement to allow unique tokens to be managed, owned, and traded.
			It does not mandate a standard for token metadata or restrict adding supplemental functions.




			<br>
			<br>
			<h2 id="high-level-goals">
				<strong>High Level Goals of this Sprint</strong>
			</h2>
			<hr>
			<ul>
				<li>Learn the defferince between the non-fungible tokens vs the normal token.</li>
				<li>Learn more about the smart contracts and implement a complex smart contracts.</li>
				<li>Learn how to use truffle framework to make your life as Ethereum developer more easier</li>
				<li>Learn how to deal with your contract form your web app.</li>
				<li>Practice using web3 to control every thing on your contract.</li>
			</ul>
			<br>
			<br>

			<h2 id="getting-started">
				<strong>Getting Started and Project Set Up</strong>
			</h2>
			<hr>
			<h3>Get the smart contracts starter</h3>

			<ul>
				<li>
					fork the repository that given to form the instructional team
				</li>
				<li>
					clone it to your computer
				</li>
				<li>
					open the project folder and run
					<code>npm install</code> to install the node dependencies.
				</li>
				<li>
					open ganache and be sure to set the port in the settings to
					<code>8545</code>
					if you still don't have ganache installed on your machine you can install from
					<a href="https://truffleframework.com/ganache"> here</a>
				</li>
				<li>
					if you don't have truffle installed globaly on your machine you need to install it by writing this command on terminal
					<code>npm install -g truffle</code>
				</li>

			</ul>

			<br>
			<br>






			<h1 id="theproject">
				<strong>The Project</strong>
			</h1>

			<hr>

			<h2>- Bare minimum requirements</h2>
			<ul>
				<li>
					if you already have truffle installed globaly on your machine so run the smart contracts test using this command
					<code>truffle test</code>
				</li>
				<li>
					to make the test pass you need to modify the methods that is located in
					<code>~/contracts/ERC721BasicToken.sol</code>
				</li>
				<li>
					follow the comments and the test to implement a fully working smart contract.
				</li>
			</ul>
			<br>
			<br>
			<h2>- Advanced</h2>

			<ul>
				<li>
					<p>
						after finishing the main ERC-721 standard smart contract now lets make the smart contract perfect and fully functional
					</p>
					<p>
						open the full ERC-721 token smart contract
						<code>~/contracts/ERC721Token.sol</code>
						that is implementing the contract that you have done and start modifying the methods to be full working.

					</p>
				</li>

			</ul>

			<br>
			<br>


			<h1 id="extracredit">Extra Credit</h1>
			<ul>
				<li>
					when you get the smart contract fully working now you need to build the functions that interact with smart contract via web3
					on the client side.
				</li>
				<li>
					to modify the methods you can
					<code>~/src/js/app.js</code>
				</li>
				<li>run the lite server to run the website on a local host by running
					<code>npm run dev</code>
				</li>
				<li>when you run it for the first time it will not be functional but your job is to implement the methods correctly and use
					the method
					<code>App.setMesagge</code> to show the result to the end user
				</li>
				<li>be sure to compile the smart contract and deploy it on ganache using truffle by using this command
					<code>truffle migrate --compile-all --reset</code>
				</li>
			</ul>
			<br>
			<br>
			<h1 id="extracredit">nightmare mode</h1>
			<ul>
				<li>
					deploy your token to ethereum rinkeby or reposten test networks or if you have a lot of money ;) deploy it to the main etherum
					network.
				</li>
			</ul>
			<hr>

		</div>

		<h1 id="useful-links">
			<strong>Useful Links</strong>
		</h1>
		<hr>
		<ul>
			<li>
				<a href="https://truffleframework.com/docs">truffle and ganache documentation</a>
			</li>
			<li>
				<a href="https://truffleframework.com/docs/ganache/overview">ganache</a>
			</li>
			<li>
				<a href="https://github.com/ethereum/web3.js/">web3 readme</a>
			</li>
			<li>
				<a href="https://web3j.readthedocs.io/en/latest/infura.html">Using Infura with web3</a>
			</li>
			<li>
				<a href="http://erc721.org/">ERC-721 website</a>
			</li>

		</ul>


	</div>


	<br>
	<br>
	<br>
	<br>

	<button class="scrollToTop btn btn-primary">
		<i class="fas fa-angle-double-up"></i>
	</button>

	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>

	<script>
		$(document).ready(function () {

			$(function () {

				$('a[href*="#"]:not([href="#"])').click(function () {

					if (location.pathname.replace(/^\//, '') == this.pathname.replace(/^\//, '') && location.hostname == this.hostname) {

						var target = $(this.hash);

						target = target.length ? target : $('[name=' + this.hash.slice(1) + ']');

						if (target.length) {

							$('html, body').animate({

								scrollTop: target.offset().top

							}, 900);

							return false;

						}

					}

				});

			});

			//Check to see if the window is top if not then display button

			$(window).scroll(function () {

				if ($(this).scrollTop() > 100) {

					$('.scrollToTop').fadeIn();

				} else {

					$('.scrollToTop').fadeOut();

				}

			});

			//Click event to scroll to top

			$('.scrollToTop').click(function () {

				$('html, body').animate({
					scrollTop: 0
				}, 800);

				return false;

			});

		});
	</script>

	</div>

</body>

</html>
