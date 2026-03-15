# Chapter 18: Cascade

Dr. Elena Marsh | Crew Selection Office, Houston

September 3, 2033 | 8:14 AM CST

Compass arrived at its target on August 19 and began transmitting four days later, after the instruments had completed their calibration sequence and the mission team at JPL had confirmed signal integrity. The first data package was 2.3 terabytes. The second, transmitted eleven days later, was larger.

Elena was not on the Compass mission team and did not have direct access to the data. What she had was a briefing summary from Dr. Harrison, delivered by secure channel on the morning of September 3rd, and the specific quality of Harrison's voice on the briefing call, which she had learned over three years to read as accurately as she read the text.

Harrison's voice said: the data is what we needed and it is also worse than we hoped.

The asteroid's internal structure was a cohesion gradient rather than a uniform rubble pile. The outer shell, three hundred to four hundred meters beneath the surface, had a higher cohesion index than the models had predicted, which was good, it meant the kinetic impactors would transfer momentum more efficiently than the pessimistic scenario had modeled. The core, below that, was looser than expected. Not fragmentation-risk loose. But the distribution of mass concentrations within the core meant that the targeting solution had a narrower optimal window than the JPL team had been working with.

Narrower was not impossible. Harrison was careful about that. The targeting problem was solvable with the data they now had. The team had been working with a range of possible solutions and was now working with a smaller range. The probability estimate, Harrison said, was currently in revision.

"What's the preliminary figure," Elena asked.

"They're not releasing one yet. The model update is ongoing."

"Harrison."

A pause. "The initial analyst consensus before formal review is in the high forties."

Elena wrote it down. High forties. She sat with it for a moment, then asked the next question. "Where does that put the mission parameters?"

"The mission parameters for Phoenix are unchanged. Maria Webb's mission is still viable and still the optimal approach. The trajectory, the timing, the impactor deployment protocol, all of those are unchanged. What's changed is the margin for targeting error. It's tighter." Harrison paused again. "The mission has to go exactly right."

"Missions have to go exactly right."

"This one has a narrower definition of right than we had last year." He was being precise because precision was how he managed the gap between what the data said and what anyone wanted the data to say. "I'll have the full revised briefing to you within two weeks."

Elena ended the call and sat at her desk.

High forties.

* * *

The cryosleep system prototype had been installed in the ship's mid-section in June. Installation was a three-month operation: six hundred units, each one a coffin-sized pod of aluminum and insulated composite with the temperature regulation and metabolic monitoring systems built into the wall, each one requiring individual calibration against the ship's environmental control network. The installation team had finished on schedule, which was the phrase the briefings always used when they wanted to convey that something had been done correctly without appearing to be surprised by it.

The first full-scale test was scheduled for October. Not with human subjects, the test protocol used biological proxies, cellular cultures and organ-analog systems developed specifically to validate the cryosleep environment without requiring a living person. Eighty-six pods running simultaneously. Two weeks of cold cycle followed by a controlled revival sequence. The results would determine whether the second test, the one with a small number of human volunteers, could proceed on schedule.

Elena had been involved in the test protocol design and was listed as a technical reviewer on the results analysis team. She had spent eighteen months on this, reading the thermal regulation papers and the metabolic suppression literature and the extended protocols that had come out of the Nagoya work and the follow-on studies from the University of Tokyo and Oslo. She understood the system better than she had when she'd commissioned Kim's initial analysis in 2027, which meant she understood more precisely where the risks were.

The risk she had been thinking about for eight months was the revival sequence.

Suppressing metabolism was, from a systems engineering standpoint, the easier problem. The challenge was the revival: the coordinated restart of cellular processes that had been suspended for forty years, across four thousand bodies, in an environment that had changed in ways the designers could not fully predict over a four-decade transit. The revival protocol had been tested in increasingly long durations: eleven days in 2024, which was the Nagoya result; twenty-six days in 2030, with a cellular proxy system; one hundred and twelve days in 2032, also with proxies. Each test had produced results within the acceptable parameters.

The October test would be three hundred and eighty days. The longest duration by a factor of more than three.

* * *

The test data began coming in on a Tuesday in October.

Elena was in the office, working on the second-cohort selection assessments, when the first anomaly flag appeared on the monitoring dashboard. She looked at it and looked at the timestamp and understood that the pod number indicated was in the eastern bank of the test array and that "anomaly" was the dashboard's category for any reading outside two standard deviations of the baseline.

She refreshed. Two more flags. Different pods.

She called Kim.

Kim was already in the lab. "I see them," she said before Elena finished the sentence.

"What are we looking at."

"Temperature gradient deviation in the eastern bank. The individual pod readings are within spec but the inter-pod differential is building." The sound of keys. "It shouldn't be building. The thermal regulation should be compensating."

"Is it compensating?"

"It's running at one hundred and eight percent of baseline load." A pause. "It's working harder than it should be to hold the gradient."

Elena stood up and walked to the window. Outside, the Houston afternoon was bright and hot in the way it was always hot in October now, the summer extending in both directions. "Is this a sensor error or a system behavior?"

"I need forty minutes to distinguish them."

"Call me when you know."

She went back to the desk and sat with the dashboard. In forty minutes the eastern bank had twelve flags. The thermal regulation load had increased to one hundred and sixteen percent. The pod readings were still within spec, which meant the biological proxies in the eastern bank were not yet showing stress.

Kim called back in thirty-eight minutes. "System behavior," she said. "Not sensor error. The thermal regulation architecture has a cascade vulnerability in extended cold operation. When the inter-pod differential reaches a specific threshold, the regulation system shifts to a compensatory mode that increases energy draw. The increased draw creates additional heat load. Which pushes the regulation system harder."

"It feeds itself."

"Slowly. But yes." Another pause. "In the current test conditions, the cascade will stabilize. The system has enough headroom to compensate indefinitely at current load. The biological proxies will complete the test without degradation."

"But," Elena said.

"But the cascade vulnerability scales with pod count. We tested this configuration with eighty-six units. The ship runs four thousand, two hundred and sixteen. At full ship scale, the cascade may not stabilize."

Elena looked at the dashboard. Twelve flags in the eastern bank, the thermal load building, the system compensating. A prototype demonstrating, at small scale, a behavior that could become uncontrollable at the scale they actually needed.

"How certain are you," she said.

"I'm certain about the cascade mechanism. The scaling behavior is modeled, not tested. The model says the cascade becomes unstable above approximately six hundred and fifty units in thermal proximity to each other."

"The habitation rings."

"Yes." Kim's voice was level in the way it was level when she had thought something through and was presenting the conclusion she had arrived at. "Each habitation ring has approximately fourteen hundred pods in the installation configuration."

Elena sat with this.

Fourteen hundred pods per ring. Three habitation rings. A cascade that might become unstable above six hundred and fifty units. This was not a calibration issue. This was not an edge case in the operating envelope. This was the system demonstrating, at one-twentieth of operational scale, that it might not work at operational scale.

"Send me the model," she said.

"It's in your inbox."

"Don't release this internally yet. I need to read the model before anyone else has a response to form."

"Understood."

Elena opened the model. She read it for two hours, which was not enough time to verify it but was enough time to understand the architecture of the argument Kim was making and where the assumptions were. The assumptions were defensible. The model was not obviously wrong.

She called Novak at Luna Base.

"I need to tell you something," she said when Novak picked up.

"Go ahead."

Elena described the cascade vulnerability in the terms Kim had used: the mechanism, the scaling behavior, the model, the threshold.

Novak listened without interrupting. This was Novak's quality, the one Elena had relied on across six years of this project: she processed information before she responded to it, which meant her responses were worth something.

"The ship's thermal regulation architecture," Novak said when Elena finished. "It can be modified."

"Yes. The question is how much modification and what it costs in terms of timeline."

"What does Kim's model say?"

"She hasn't modeled the modification yet. That's the next step."

"How long."

"A week to model. Then engineering review. If the modification is structural, we're looking at a construction pause."

"How long a pause."

"I don't know yet. That's the week of modeling."

Novak was quiet for a moment. Elena could hear the background noise of Luna Base, the ventilation hum and the faint echo that pressurized habitats always had. "The drive integration timeline," Novak said.

"I know."

"If we pause construction for structural modification to the thermal regulation architecture, we absorb the timeline margin."

"I know."

"And the modification has to be complete before crew loading. Which has to be complete before the departure window."

"I know all of this, Patricia." Elena used the name deliberately, which she didn't do often. "I'm telling you before the formal report goes up the chain because I want you to have time to think, not react. This is solvable. I believe this is solvable. I need a week to know how."

Another silence. Then Novak said: "The probability revision from Compass."

"High forties. Preliminary."

"So the deflection margin has narrowed and the ship's cryosleep architecture may require structural modification."

"Yes."

"At the same time."

"Yes."

Novak was quiet for ten seconds. Elena counted.

"Get me Kim's modification model as soon as it exists," Novak said. "I'll have the engineering team ready to review the same day."

"Thank you."

"Elena." A pause. "This is what margins are for."

The call ended.

Elena sat in the office until nine. She read Kim's cascade model twice more. She looked at the test dashboard, the eastern bank stabilized now, the proxies nominal, the system compensating with one hundred and nineteen percent of baseline load.

She thought about four thousand people in cold sleep for forty years.

She thought about high forties and a narrow targeting window and a cascade that fed itself.

She thought about margins.

Then she opened a new document and began drafting the internal report, because the formal version of what she'd told Novak needed to exist in writing before morning, and the writing was the work, and the work was what you did when the week in front of you had become harder than the week you'd planned for.

She wrote until midnight. Then she drove home and set the alarm for five and went to sleep, because the modification model would be in her inbox in a week and she needed to be ready to read it.

The ship existed. It could be fixed. She was going to fix it.

,  END OF CHAPTER 18 , 

ACT THREE

Fracture · 2034–2038