---
title: rock paper scissors microbit game
layout: post
author: littman.lewis
permalink: /rock-paper-scissors-microbit-game/
source-id: 137909iFYbF2ndl-3bCAygPmlqiChRITQk_1R5-pVMAM
published: true
---
// When the BBC micro:bit runs.

function onStart(  ) {

	

}

function onShake(  ) {

	globals.Rn = Random.number(0, 2);

	if (globals.Rn == 0) {

		

		microbit.draw(Pattern("01110.11111.11111.11111.01110"));

		

	}

	

	else if (globals.Rn == 1) {

		

		microbit.draw(Pattern("01110.01110.01110.01110.01110"));

		

	}

	

	else if (globals.Rn == 2) {

		

		microbit.draw(Pattern("00100.00100.01111.00100.00000"));

		

	}

	

	

}

