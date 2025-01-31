# WatsonX and Emergence AI Web Orchestrator Integration

## Steps to Integrate:
1. Download or clone this GitHub repository to get access to the 3 files locally.

2. Navigate to Skills Studio in WatsonX Orchestrate

3. Upload the CreateEmergenceInstance.json and PollUntilComplete.json files directly to WatsonX Orchestrate via Create --> ImportAPI.

4. Publish these two skills by clicking "Enhance skill" for each one, and then clicking "Publish"

5. Navigate to the WatsonX Legacy Chat, and open the "Skills Catalog"

6. Search for "Emergence" in the search bar and you should see the two skills that you published.

7. For each of these skills, click "Connect" in the top right-hand corner and paste your Emergence API Key.

8. Now, click "Add" for each. CreateEmergenceInstance and PollUntilComplete have now been added!

9. Navigate back to Skills Studio and click Create, followed by Skill flow from the dropdown.

10. Drag the CreateEmergenceInstance skill into the editor, followed by the PollUntilComplete skill (one after the other in the sequence)

11. Click "Actions" in the right-hand corner, and select "Enhance skill" in the drop down

12. "Save and close", add the necessary trigger phrases, and publish the skill flow.

13. Navigate back to the "Skills Catalog" in WatsonX Legacy Chat

14. Search for "Skill flows", and within Skill flows search for "Emergence"

15. Add the Emergence Web Orchestrator skill flow 

16. Navigate back to the WatsonX Legacy Chat


You can now use Emergence's Web Orchestrator inside of WatsonX Orchestrator! Type in commands like "I have a web-related task" or "I need Emergence", and WatsonX Orchestrate will automatically begin using Emergence's Web Orchestrator.

