<h1>Carpenter V1</h1>
<hr><p>Multiplayer Simulation Game Project</p><h2>Features</h2>
<hr><ul>
<li>Unreal Engine 5.7</li>
</ul><ul>
<li>Multiplayer</li>
</ul><h2>Setup</h2>
<hr><p>Testing Instructions
To experience the project as intended, please follow these steps:</p><h5>Steps</h5><ul>
<li>Level: Open the Lvl_ThirdPerson map.</li>
</ul><ul>
<li>Multiplayer Settings:  Set Number of Players to 2 or 4.</li>
</ul><ul>
<li>Set Net Mode to Play As Listen Server.</li>
</ul><ul>
<li>Launch: Click Play; your character will automatically spawn at the PlayerStart location.</li>
</ul><ul>
<li>Gameplay Loop:  Pick up an item from the production stations.</li>
</ul><ul>
<li>Paint the item with the requested color.</li>
</ul><ul>
<li>Bring it to the Delivery Zone and observe the budget increase and real-time HUD updates.</li>
</ul><h2>Improvements</h2>
<hr><ul>
<li>BP_Order	The primary data source for order management; it defines the specific workflow and processing stages required for each item.</li>
</ul><ul>
<li>BP_CarveMachine	An interactive carving station where raw materials are shaped into their base forms.</li>
</ul><ul>
<li>BP_PaintStation	A specialized station where shaped items are dynamically textured and painted based on order requirements.</li>
</ul>
<ul>
<li>BP_DeliveryZone	The final validation area where delivered items are checked against active orders, budget is updated, and actors are destroyed.</li>
</ul>
