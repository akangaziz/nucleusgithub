# nucleusgithub
This project is the open source version of ThirdBrainFx's project run by ThirdBrain, a Swiss Corporation since 2012, registred as Wealth Manager in Switzerland.

This version allows you to go really beyond all what you can see in open source with link between Metatrader 4 <> xAPI <> Php <> Mysql based on LAMPP stacks.

Basic description of Nucleus (on GitHub) : 
This first version do basically : 

1 - Take your trading orders (BUY/SELL/CLOSE) (Pending Orders are not taken) under any Metatrader 4 hosted anywhere from any brokers and display them in a webpage.

2 - Filter this order via the portfolio of a trader/user (composed of a couple strategy(robo-advisor)/instrument and send them to his trading account respecting rules and risk management fixed by the users.

In this GITHUB version, you don't have for the moment :

3 - All the cron needed in backoffice to compute correlation, CFD advices, DB cleaning ect..

4 - The Daemon who parse the journal of orders to send to each account (using xAPI of xopenhub you can see with XTB broker) which is running in a screen in daemon

The open source project is now carried by Duvivier Inc, an US CORP which will take to next level the code.

Pierre Jean Duvivier is the Lead Developer, the COO of ThirdBrain SA and the CEO of Duvivier Inc. 

The code is under Creative Common License with Attribution Rights. 

Licensees may copy, distribute, display and perform the work and make derivative works and remixes based on it only if they give the author or licensor the credits (attribution) in the manner specified by these.

Then please send an email to pierre@duvivier.xyz to allow any commercial use of this scripts or any proposal to help.

Advanced description.

This framework helps you to :

1 - Send the order and history from any MT4 (metatrader 4) to an MYSQL DB : it could be manual trading or automatic trading. No matter. ThirdBrain Sa run up to 50 MT4 sessions on many instruments sending the orders you can check here :
 https://www.thirdbrainfx.com (with our brokerage tools with xOpenHub) or inside the Mirror Trader with FXCM or FXDD as brokers. Orders are sent by the MT4, injected in a DB and displayed on the front office website, first. (what you can see on our website https://www.thirdbrainfx.com)

2 - Allow client to build their portfolio and replicate on their account (with xOPenhub/xaPI) or inside the tool (in B-BOOK mode) the trades coming from the robo-advisor selected.

3 - Manage 1'500 instruments for Forex to Equities following the same ranking system (only with A-BOOK with xAPI for equities).

4 - Allow website to display using rich interface (jQuery) in 2D or 3D (with Three.js) the trades sent by the Robo-Advisor(s). There is an unlimited of strategies which can run.

5 - Please see the system requirement to run all this stuff : Php, Mysql , better 2 linux server : one for the https:// and one for the DB. The DB receiver need to be in Lighttpd or NGinx. Apache is fine for the frontend.

6 - get PHP bridges for : xAPI, Tradency (Mirror Trader)

The framework is already running with live client in closed mode since 2014. We will step by step release all the part of this very complex system which bring us success with ThirdBrain SA.

The first step will be the Injector (send the MT4 orders to the Mysql DB) and the display (you can see on the website https://www.thirdbrainfx.com). 

Warning : this version is a version without security embedded to allow educationnal lessons managing the security aspect - which is huge - a part because there is system aspect to understand before and a mix between settings in the code (not present in this GitHub Version) and Linux securisation of servers. All will be developed in direct coach courses. Then don't use this version "live" if you don't have any experience related to security matter because there is a lot of fix to apply to switch live.

Go directly to the WIKI :
https://github.com/thirdbrainsa/nucleusgithub/wiki

To start after downloaded the code.
