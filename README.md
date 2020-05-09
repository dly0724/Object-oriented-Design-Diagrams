# Object-oriented-Design-Diagram

You have again been hired by the Medieval Faire. They have tournaments and you have to create a system to track the tournament results. Each tournament takes place on a given date and time. A tournament pits knights againt each other in events. One event is Cabbaging. In Cabbaging, a cabbage is placed on a pole. Each knight gallops at the cabbage with a sword, trying to cut a piece off of the top of the cabbage. The knight who cuts the smallest piece wins. Another event is Jousting. In Jousting, two knights ride towards each other with lances, trying to hit the shield of their opponent with the lance. A score is assigned to each knight based on these criteria:
Lance is shattered - 3 points
Lance tip is broken - 2 points
Lance makes contact, but does not break - 1 point
Lance does not contact opponent - 0 points
Judges can also award penalty points for minor infractions, such as not presenting a good target, not cantering or galloping, or dropping the lance. If the lance hits a horse, the participate is disqualified.
Your solution must make it easy to add additional types of events in the future beyond these two events.


Scenario: We have five Knights: Sir Godfrey, Sir Brienne of Tarth, Sir Cumferance, Sir Kull, and Sir Not Appearing in this Scenario. For the tournament on 9/2/2019, event 1 occurred at 1:07pm and is Cabbaging. Godfrey, Brienne, and Cumferance took part in this event. Godfrey went first and cut 2 inches of cabbage and Brienne went second and cut 1/2 inch. Cumferance missed completely (zero inches).
This is followed at 1:15pm by event 2, a joust between Godfrey and Cumferance. Godfrey scored 2 points and Cumferance scored zero. Event 3 is a joust between Brienne and Kull. Brienne scored 3 points. Kull was assessed a 2 point penalty for flinching to avoid contact. Event 4 is a joust between Godfrey and Brienne (winners of the previous two jousts). Brienne scored 3 points. Godfrey was disqualified in this round. Brienne was declared the winner!
