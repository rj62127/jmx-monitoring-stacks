
# Confluent CP Demo with JMX Monitoring Setup

## Step 1: Clone the cp-demo repository

Clone the Confluent demo repository using the following command:

```bash
git clone https://github.com/confluentinc/cp-demo.git
```

Make sure to clone this into the root directory where the `jmx-monitoring-stacks` is placed.

## Step 2: Set the CP_DEMO_HOME environment variable

Once cloned, set the `CP_DEMO_HOME` environment variable by running:

```bash
export CP_DEMO_HOME=/path/to/cp-demo
```

Replace `/path/to/cp-demo` with the actual path where you have cloned the repository.

## Step 3: Navigate to JMX Monitoring Directory

Change your directory to the JMX monitoring stack location:

```bash
cd jmx-monitoring-stacks/jmxexporter-prometheus-grafana
```

## Step 4: Run the Start Script

Execute the following command to start the monitoring stack:

```bash
sudo ./start.sh
```

This will initiate the JMX monitoring stack using Prometheus and Grafana.

## Conclusion

You have now successfully set up the Confluent CP demo with JMX monitoring.


# Result

![alt text](<images/Screenshot from 2024-10-08 12-41-29.png>)
![alt text](<images/Screenshot from 2024-10-08 12-43-33.png>)
![alt text](<images/Screenshot from 2024-10-08 12-43-53.png>)
![alt text](<images/Screenshot from 2024-10-08 12-43-59.png>)
![alt text](<images/Screenshot from 2024-10-08 12-44-03.png>)
![alt text](<images/Screenshot from 2024-10-08 12-44-18.png>)
![alt text](<images/Screenshot from 2024-10-08 12-44-37.png>)
![alt text](<images/Screenshot from 2024-10-08 12-44-48.png>)
![alt text](<images/Screenshot from 2024-10-08 12-45-13.png>)