# SpeedSense
SpeedSense is an advanced iperf3-based internet speed test application for Windows, designed to measure real network performance, not inflated marketing numbers.

Unlike typical browser speed tests, SpeedSense focuses on throughput, latency under load, bufferbloat, stability, and TCP efficiency — giving you a true picture of your connection quality.

✨ Key Features
📶 Accurate Speed Testing

TCP download & upload testing using iperf3

Reverse-mode download testing (server → client)

Single-stream and multi-stream TCP modes

Real-time speed updates with smooth animated gauges

🌍 Smart Global Server Selection

Automatic server selection based on:

Lowest latency

TCP reachability

Download capability

Manual server selection by country & city

Large global server list (Europe, USA, Asia, Middle East, Africa)

Intelligent server rotation to avoid overload

Automatic failover if a server fails

📡 Advanced Network Metrics

SpeedSense measures far more than just speed:

Latency under load (download & upload)

Bufferbloat detection

Jitter (95th percentile)

Packet loss estimation

TCP congestion control detection

TCP efficiency vs link speed

Traffic shaping probability detection

Path MTU & recommended MSS

🎮 Real-World Quality Analysis

Your connection is evaluated for real usage scenarios:

🎮 Online gaming

📞 Video calls

📺 Streaming (1080p / 1440p / 4K)

🌐 Web browsing

Each test produces:

Connection Quality Grade (A+ to D)

Stability rating (Stable / Fluctuating / Unstable)

Actionable recommendations

📊 Professional Visualization

Live high-performance speed graph

Smooth animated speed gauges

Adjustable gauge scale (100 / 500 / 1000 Mbps)

Final interactive speed chart with:

Smoothed curves

Peak markers

Average lines

Download → upload phase marker

🧠 Intelligent Detection

Detects Wi-Fi vs Ethernet

Estimates Wi-Fi signal strength

Identifies local interface bottlenecks

Detects weak Wi-Fi conditions

Saves full test history automatically

🖥 System Requirements

Windows 10 / 11 (64-bit)

.NET Framework (included with Windows)

iperf3.exe (user-provided)

⚙️ How to Use

Download SpeedSense from the Releases page

Launch the application

Select iperf3.exe when prompted

Choose:

Automatic or Manual server mode

Single-stream or Multi-stream TCP

Click Start Test

View live results and final analysis

📁 Test Results

All test results are saved locally to:

TestResults.txt


Each entry includes:

Server location

Download & upload speed

Latency & jitter

Bufferbloat

Packet loss & confidence

TCP efficiency

Quality grade

🔒 License

SpeedSense is free to use, but closed-source.

✅ Free for personal & commercial use

❌ No redistribution or resale

❌ No reverse engineering or modification

❌ No source code included

See LICENSE.txt for full terms.

💬 Support & Feedback

If you have:

Bug reports

Feature requests

Improvement ideas

You can open a GitHub Issue
or contact me on Discord (add your Discord here)

🛣 Planned Features (Roadmap)

UDP testing mode

Export results (CSV / JSON)

Portable version

Dark / Light theme toggle

Per-ISP comparison

⭐ Final Note

SpeedSense is built for users who care about truthful network measurements, not browser-based approximations.

If you want to understand how your internet really behaves under load, this tool is for you.


Third-Party Software:
SpeedSense includes iperf3, which is licensed under the BSD 3-Clause License.
