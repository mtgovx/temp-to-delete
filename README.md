# Convert Avro to JSON
1. Download hadoop-common https://github.com/srccodes/hadoop-common-2.2.0-bin
2. Extract to C:\Program Files
3. Run the following in PowerShell to set the HADOOP_HOME variable at the system level: [System.Environment]::SetEnvironmentVariable("HADOOP_HOME", "C:\Program Files\hadoop-common-2.2.0-bin-master", [System.EnvironmentVariableTarget]::Machine)
4. Add HADOOP_HOME to path as "%HADOOP_HOME%\bin"
5. Run the following command in PowerShell to install AvroTools: Install-Module -Name AvroTools -RequiredVersion 1.3
6. Import-Module AvroTools
