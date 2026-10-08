

<table>
    <tr>
        <th>Gradle Root Project</th>
        <th>Requested Tasks</th>
        <th>Gradle Version</th>
        <th>Build Outcome</th>
        <th>Build&nbsp;Scan®</th>
    </tr>
    <tr>
        <td>GuideLens</td>
        <td>assembleDebug</td>
        <td align='center'>8.7</td>
        <td align='center'>:x:</td>
        <td><a href="https://scans.gradle.com" rel="nofollow" target="_blank"><img src="https://img.shields.io/badge/Not%20published-lightgrey" alt="Build Scan not published" /></a></td>
    </tr>
</table>
    
<details>
<summary><h4>Caching for Gradle actions was enabled - expand for details</h4></summary>

- [Cache was enabled](https://github.com/gradle/actions/blob/main/docs/setup-gradle.md#caching-build-state-between-jobs). Action attempted to both restore and save the Gradle User Home.
- [Cache cleanup was disabled due to build failure](https://github.com/gradle/actions/blob/main/docs/setup-gradle.md#configuring-cache-cleanup). Use `cache-cleanup: always` to override this behavior.


<table>
    <tr><td></td><th>Count</th><th>Total Size (Mb)</th><th>Total Time (ms)</tr>
    <tr><td>Entries Restored</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
    </tr>
    <tr><td>Entries Saved</td>
        <td>5</td>
        <td>341</td>
        <td>12837</td>
    </tr>
</table>
    

<h5>Cache Entry Details</h5>
<pre>
    Entry: Gradle User Home
    Requested Key : gradle-home-v1|Linux-X64|build[620c74083efa5b88ef904c2356f72d31]-53cc476486f9cd15ad45652ed382dead2559f52a
    Restored  Key : 
              Size: 
              Time: 
              (Entry not restored: no match found)
    Saved     Key : gradle-home-v1|Linux-X64|build[620c74083efa5b88ef904c2356f72d31]-53cc476486f9cd15ad45652ed382dead2559f52a
              Size: 0 MB (477002 B)
              Time: 1290 ms
              (Entry saved)
---
Entry: /home/runner/.gradle/caches/modules-*/files-*/*/*/*/*
    Requested Key : 
    Restored  Key : 
              Size: 
              Time: 
              (Entry not restored: not requested)
    Saved     Key : gradle-dependencies-v1-1849d138cc05d11611e25acb00520ae9
              Size: 196 MB (205727547 B)
              Time: 3887 ms
              (Entry saved)
---
Entry: /home/runner/.gradle/caches/jars-*/*/
    Requested Key : 
    Restored  Key : 
              Size: 
              Time: 
              (Entry not restored: not requested)
    Saved     Key : gradle-instrumented-jars-v1-0efc5909bd40cd3f810d620c5a031a97
              Size: 0 MB (89325 B)
              Time: 1230 ms
              (Entry saved)
---
Entry: /home/runner/.gradle/caches/*/groovy-dsl/*/
    Requested Key : 
    Restored  Key : 
              Size: 
              Time: 
              (Entry not restored: not requested)
    Saved     Key : gradle-groovy-dsl-v1-4dbfdff14cfae036027a26ed5c2f3a52
              Size: 0 MB (139127 B)
              Time: 1270 ms
              (Entry saved)
---
Entry: /home/runner/.gradle/caches/transforms-4/*/
/home/runner/.gradle/caches/*/transforms/*/
    Requested Key : 
    Restored  Key : 
              Size: 
              Time: 
              (Entry not restored: not requested)
    Saved     Key : gradle-transforms-v1-565b5e276443484f0425828f8c34ea80
              Size: 144 MB (151063804 B)
              Time: 5160 ms
              (Entry saved)

</pre>
</details>
    
