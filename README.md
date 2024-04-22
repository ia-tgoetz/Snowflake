# Snowflake
SnowflakeEnvironment

## Demo Setup

<ol>
    <li>Clear Schema In Snowflake Console</li>
    <ul>
      <li>Project ► Worksheets ► Clear Schema</li>
      <li>Run All</li>
    </ul>
    <li>Open Putty</li>
    <ul>
      <li>sudo systemctl start ibsnow.service</li>
    </ul>
</ol>

## Demo
<ol>
    <li>Open Gateway ► Transmission</li>
    <li>Navigate to Snowflake Console</li>
    <li>From Gateway, Turn MQTT Transmission On</li>
</ol>

## Demo Shutdown

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