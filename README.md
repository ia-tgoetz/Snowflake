# Snowflake
SnowflakeEnvironment

### Demo Setup

<ol>
    <li>Clear Schema In Snowflake Console</li>
    <ul>
      <li>Project ► Worksheets ► Clear Schema</li>
      <li>Run All</li>
    </ul>
     <li>Open AWS salengdev</li>
    <ul>
      <li>us-west-2</li>
      <li>Select your instance and do an Instance State► Start Instance </li>  
      <li>Right Click on Instance after started ►Instance settings► Modify instance metadata options</li>  
      <li>IMDSv2 set to Optional</li> 
      <li>Note Public IP</li> 
    </ul>   
    <li>Open Putty</li>
    <ul>
      <li>ubuntu@{publicIP}</li>
      <li>creds► SE Dev SSH key</li>
      <li>sudo systemctl start ibsnow.service</li>
    </ul>
</ol>

## Demo
<ol>
    <li>Open Gateway ► Transmission</li>
    <li>Change Server IP to {publicIP} in Transmission</li>
    <li>Navigate to Snowflake Console</li>
    <li>From Gateway, Turn MQTT Transmission On</li>
</ol>

### Demo Shutdown

<ol>
    <li>Open Putty</li>
    <ul>
      <li>sudo systemctl stop ibsnow.service</li>
    </ul>
    <li>Clear Schema In Snowflake Console</li>
    <ul>
      <li>Project ► Worksheets ► Clear Schema</li>
      <li>Run All</li>
    </ul>

</ol>
