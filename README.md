<img src="https://raw.githubusercontent.com/hershyz/oracle/main/assets/oracle.png">
<p><i>LIDAR Wearable Navigational System for the Visually Impaired.</i></p>

<br>

<h3>Background Information</h3>
<p>
253 million people worldwide including 20.6 million Americans are visually impaired. Research acknowledges that 42% of these visually impaired people have trouble navigating everyday objects in their environments.
</p>

<h3>Goal</h3>
<p>
To alleviate the stressors experienced by the visually impaired when traversing unfamiliar environments by leveraging LiDAR mesh classifications and supplemental image classifiers to non-intrusively relay sufficient descriptions of the surroundings to the user.
</p>

<h3>How it Works</h3>
<ul>
  <li>We used the LiDAR sensor (iPhone 12 Pro) to classify objects that were relatively geometrically simple from a depthmap. The LiDAR sensor doubled as a distance measuring device, capable of measuring object distances up to 5 meters.</li>
  <li>For objects that were more geometrically complex, we used Swift's CoreML library for image classifications.</li>
  <li>Finally, we used Swift's AVFoundation library to non-intrusively relay descriptions of surroundings to the user.</li>
</ul>
