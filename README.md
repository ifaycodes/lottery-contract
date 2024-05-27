# Random Raffle Contract

## About
Allow users to enter the raffle after paying an entrance fee.

Select a random winner for the lottery after some time has elapsed.

## System
Let users enter the raffle

--Automated--
Update raffle state so that new users can't enter while calculating winner
Use Chainlink VRF for random number used to calculate winner
Pick winner and send lottery price
