  <div class="description user_content "><div id="bootcamp">
<img style="display: none;" src="https://static.bc-edx.com/data/dl-1-2/m14/lms/img/banner.jpg" alt="lesson banner">
    <h3>Background</h3>
    <p>In this assignment, you will build an interactive dashboard to explore the <a href="http://robdunnlab.com/projects/belly-button-biodiversity/">Belly Button Biodiversity dataset</a>, which catalogs the microbes that colonize human navels.</p>
    <p>The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.</p>
    <h3>Before You Begin</h3>
    <ol>
        <li>
            <p>Create a new repository for this project called <code>belly-button-challenge</code>. <em>Do not add this Challenge to an existing repository</em>.</p>
        </li>
        <li>
            <p>Clone the new repository to your computer.</p>
        </li>
        <li>
            <p>Inside your local git repository, copy the files from in the <code>StarterCode</code> folder contained within the Module 14 Challenge zip file. i.e. <code>index.html</code>, <code>samples.json</code>, and the <code>static</code> folder.</p>
            <blockquote class="callout note">
<strong>note</strong>
                <p>You will not be required to access the samples.json file locally, but it is provided for reference.</p>
            </blockquote>
        </li>
        <li>
            <p>Push the above changes to GitHub.</p>
        </li>
        <li>
            <p>Deploy the new repository to GitHub Pages.</p>
        </li>
    </ol>
    <h3>Files</h3>
    <p>Download the following files to help you get started:</p>
    <p><a href="https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/Starter_Code.zip">Module 14 Challenge files</a></p>
    <h3>Instructions</h3>
    <p>Complete the following steps:</p>
    <ol>
        <li>
            <p>Use the D3 library to read in <code>samples.json</code> from the URL <code>https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json</code>.</p>
        </li>
        <li>
            <p>Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.</p>
            <ul>
                <li>
                    <p>Use <code>sample_values</code> as the values for the bar chart.</p>
                </li>
                <li>
                    <p>Use <code>otu_ids</code> as the labels for the bar chart.</p>
                </li>
                <li>
                    <p>Use <code>otu_labels</code> as the hovertext for the chart.</p>
                    <p><img src="https://static.bc-edx.com/data/dl-1-2/m14/lms/img/hw01.jpg" alt="bar Chart"></p>
                </li>
            </ul>
        </li>
        <li>
            <p>Create a bubble chart that displays each sample.</p>
            <ul>
                <li>
                    <p>Use <code>otu_ids</code> for the x values.</p>
                </li>
                <li>
                    <p>Use <code>sample_values</code> for the y values.</p>
                </li>
                <li>
                    <p>Use <code>sample_values</code> for the marker size.</p>
                </li>
                <li>
                    <p>Use <code>otu_ids</code> for the marker colors.</p>
                </li>
                <li>
                    <p>Use <code>otu_labels</code> for the text values.</p>
                </li>
            </ul>
            <p><img src="https://static.bc-edx.com/data/dl-1-2/m14/lms/img/bubble_chart.jpg" alt="Bubble Chart"></p>
        </li>
        <li>
            <p>Display the sample metadata, i.e., an individual's demographic information.</p>
        </li>
        <li>
            <p>Display each key-value pair from the metadata JSON object somewhere on the page.</p>
            <p><img src="https://static.bc-edx.com/data/dl-1-2/m14/lms/img/hw03.jpg" alt="hw"></p>
        </li>
        <li>
            <p>Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:</p>
            <p><img src="https://static.bc-edx.com/data/dl-1-2/m14/lms/img/hw02.jpg" alt="hw"></p>
        </li>
        <li>
            <p>Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file</p>
        </li>
    </ol>
