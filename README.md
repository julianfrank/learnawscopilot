# Learn AWS Copilot

Learn AWS Copilot with me

## Useful Links

🏠 [Copilot Home Page](https://aws.github.io/copilot-cli/)

📦 [AWS Elastic Container Service](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/Welcome.html)

🛣️ [Amazon Container Roadmap](https://github.com/aws/containers-roadmap)

🔥❄️✔️😂 [Sample Hobby App Repository] (https://github.com/julianfrank/samplehobbyapp)

## Diagrams

### Pre-Requisites
[![](https://mermaid.ink/img/eyJjb2RlIjoiZ3JhcGggTFJcbiAgICBzdWJncmFwaCBQcmUtUmVxdWlzaXRlc1xuICAgICAgICBDbG91ZChbQ2xvdWRdKSAtLS0gQ29udGFpbmVycyhbQ29udGFpbmVyc10pXG4gICAgICAgIENvbnRhaW5lcnMgLS0tIENvbnRhaW5lclJ1bnRpbWUoW0NvbnRhaW5lciBSdW50aW1lc10pXG4gICAgICAgIENvbnRhaW5lcnMgLS0tIENvbnRhaW5lclJlcG9zaXRvcnkoW0NvbnRhaW5lciBSZXBvc2l0b3J5XSlcbiAgICAgICAgQ2xvdWQgLS0tIENsb3VkTG9ncyhbQ2xvdWQgTG9nc10pXG4gICAgICAgIENsb3VkIC0tLSBDb2RlUmVwbyhbQ29kZSBSZXBvc2l0b3JpZXNdKVxuICAgICAgICBDb2RlUmVwbyAuLT4gR2l0aHViXG4gICAgICAgIENsb3VkIC0tLSBDSUNEKFtDSS9DRF0pXG4gICAgICAgIENsb3VkIC0tLSBDU00oW0Nsb3VkIFN0YXRlIE1hbmFnZW1lbnRdKVxuICAgICAgICBDbG91ZCAtLS0gQnVpbGRlcnMoW0Nsb3VkIEJ1aWxkZXJzXSlcbiAgICBlbmQiLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOmZhbHNlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6ZmFsc2V9)](https://mermaid-js.github.io/mermaid-live-editor/edit/#eyJjb2RlIjoiZ3JhcGggTFJcbiAgICBzdWJncmFwaCBQcmUtUmVxdWlzaXRlc1xuICAgICAgICBDbG91ZChbQ2xvdWRdKSAtLS0gQ29udGFpbmVycyhbQ29udGFpbmVyc10pXG4gICAgICAgIENvbnRhaW5lcnMgLS0tIENvbnRhaW5lclJ1bnRpbWUoW0NvbnRhaW5lciBSdW50aW1lc10pXG4gICAgICAgIENvbnRhaW5lcnMgLS0tIENvbnRhaW5lclJlcG9zaXRvcnkoW0NvbnRhaW5lciBSZXBvc2l0b3J5XSlcbiAgICAgICAgQ2xvdWQgLS0tIENsb3VkTG9ncyhbQ2xvdWQgTG9nc10pXG4gICAgICAgIENsb3VkIC0tLSBDb2RlUmVwbyhbQ29kZSBSZXBvc2l0b3JpZXNdKVxuICAgICAgICBDb2RlUmVwbyAuLT4gR2l0aHViXG4gICAgICAgIENsb3VkIC0tLSBDSUNEKFtDSS9DRF0pXG4gICAgICAgIENsb3VkIC0tLSBDU00oW0Nsb3VkIFN0YXRlIE1hbmFnZW1lbnRdKVxuICAgICAgICBDbG91ZCAtLS0gQnVpbGRlcnMoW0Nsb3VkIEJ1aWxkZXJzXSlcbiAgICBlbmQiLCJtZXJtYWlkIjoie1xuICBcInRoZW1lXCI6IFwiZGVmYXVsdFwiXG59IiwidXBkYXRlRWRpdG9yIjpmYWxzZSwiYXV0b1N5bmMiOnRydWUsInVwZGF0ZURpYWdyYW0iOmZhbHNlfQ)

### AWS Cloud Services
[![](https://mermaid.ink/img/eyJjb2RlIjoiZ3JhcGggTFJcbiAgICBcbiAgICBzdWJncmFwaCBBbWF6b24gV2ViIFNlcnZpY2VzXG5cbiAgICAgICAgc3ViZ3JhcGggQ2xvdWQgU2VydmljZXNcbiAgICAgICAgICAgIEVDUiAtLT58Q29udGFpbmVyIEltYWdlfCBFQ1NcbiAgICAgICAgICAgIFxuICAgICAgICAgICAgQ2xvdWRGb3JtYXRpb24gLi0-fGVudixzdmMsam9iLHRhc2t8IEVDU1xuICAgICAgICAgICAgXG4gICAgICAgICAgICBDbG91ZEZvcm1hdGlvbiAuLT58YnVpbGQgaW5zdHJ1Y3Rpb25zfCBDbG91ZEJ1aWxkXG4gICAgICAgICAgICBDb2RlQ29tbWl0IC4tPnxDb2RlfCBDbG91ZEJ1aWxkXG4gICAgICAgICAgICBcbiAgICAgICAgICAgIENsb3VkQnVpbGQgLi0-fENvbnRhaW5lciBJbWFnZXwgRUNSXG4gICAgICAgICAgICBcbiAgICAgICAgICAgIFxuXG4gICAgICAgICAgICBDbG91ZEZvcm1hdGlvbiAuLT58bG9nc3wgQ2xvdWRXYXRjaFxuICAgICAgICAgICAgRUNTIC4tPnxsb2dzfCBDbG91ZFdhdGNoXG4gICAgICAgICAgICBFQ1IgLi0-fGxvZ3N8IENsb3VkV2F0Y2hcbiAgICAgICAgICAgIENvZGVDb21taXQgLi0-fGxvZ3N8IENsb3VkV2F0Y2hcbiAgICAgICAgICAgIENsb3VkQnVpbGQgLi0-fGxvZ3N8IENsb3VkV2F0Y2hcbiAgICAgICAgICAgIFN5c3RlbXNNYW5hZ2VyIC4tPnxsb2dzfCBDbG91ZFdhdGNoXG5cbiAgICAgICAgZW5kXG4gICAgICAgIFxuICAgIGVuZCIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6ZmFsc2UsImF1dG9TeW5jIjp0cnVlLCJ1cGRhdGVEaWFncmFtIjpmYWxzZX0)](https://mermaid-js.github.io/mermaid-live-editor/edit/#eyJjb2RlIjoiZ3JhcGggTFJcbiAgICBcbiAgICBzdWJncmFwaCBBbWF6b24gV2ViIFNlcnZpY2VzXG5cbiAgICAgICAgc3ViZ3JhcGggQ2xvdWQgU2VydmljZXNcbiAgICAgICAgICAgIEVDUiAtLT58Q29udGFpbmVyIEltYWdlfCBFQ1NcbiAgICAgICAgICAgIFxuICAgICAgICAgICAgQ2xvdWRGb3JtYXRpb24gLi0-fGVudixzdmMsam9iLHRhc2t8IEVDU1xuICAgICAgICAgICAgXG4gICAgICAgICAgICBDbG91ZEZvcm1hdGlvbiAuLT58YnVpbGQgaW5zdHJ1Y3Rpb25zfCBDbG91ZEJ1aWxkXG4gICAgICAgICAgICBDb2RlQ29tbWl0IC4tPnxDb2RlfCBDbG91ZEJ1aWxkXG4gICAgICAgICAgICBcbiAgICAgICAgICAgIENsb3VkQnVpbGQgLi0-fENvbnRhaW5lciBJbWFnZXwgRUNSXG4gICAgICAgICAgICBcbiAgICAgICAgICAgIFxuXG4gICAgICAgICAgICBDbG91ZEZvcm1hdGlvbiAuLT58bG9nc3wgQ2xvdWRXYXRjaFxuICAgICAgICAgICAgRUNTIC4tPnxsb2dzfCBDbG91ZFdhdGNoXG4gICAgICAgICAgICBFQ1IgLi0-fGxvZ3N8IENsb3VkV2F0Y2hcbiAgICAgICAgICAgIENvZGVDb21taXQgLi0-fGxvZ3N8IENsb3VkV2F0Y2hcbiAgICAgICAgICAgIENsb3VkQnVpbGQgLi0-fGxvZ3N8IENsb3VkV2F0Y2hcbiAgICAgICAgICAgIFN5c3RlbXNNYW5hZ2VyIC4tPnxsb2dzfCBDbG91ZFdhdGNoXG5cbiAgICAgICAgZW5kXG4gICAgICAgIFxuICAgIGVuZCIsIm1lcm1haWQiOiJ7XG4gIFwidGhlbWVcIjogXCJkZWZhdWx0XCJcbn0iLCJ1cGRhdGVFZGl0b3IiOmZhbHNlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6ZmFsc2V9)

### AWS Copilot CLI
[![](https://mermaid.ink/img/eyJjb2RlIjoiZ3JhcGggTFJcbiAgICBcbiAgICBzdWJncmFwaCBBbWF6b24gV2ViIFNlcnZpY2VzXG5cbiAgICAgICAgc3ViZ3JhcGggQ2xvdWQgU2VydmljZXNcbiAgICAgICAgICAgIFxuICAgICAgICAgICAgXG4gICAgICAgICAgICBDbG91ZEZvcm1hdGlvbiAuLT58VGFzayBEZWZpbml0aW9uOiBlbnYsc3ZjLGpvYix0YXNrfCBFQ1NcbiAgICAgICAgICAgIFxuXG5DbG91ZEZvcm1hdGlvbiAuLT58YXBwIGFuZCBlbnYgc3RhdGVzfCBTeXN0ZW1zTWFuYWdlcihbU3lzdGVtcyBNYW5hZ2VyXSlcbiAgICAgICAgICAgIEVDUiAtLT58Q29udGFpbmVyIEltYWdlfCBFQ1NcbiAgICAgICAgZW5kXG4gICAgICAgIFxuICAgICAgICBzdWJncmFwaCBDb1BpbG90IENMSVxuICAgICAgICAgICAgQ1BBcHAoW2FwcF0pIC4tfENvbmZpZ3VyYXRpb258IENsb3VkRm9ybWF0aW9uXG4gICAgICAgICAgICBDUEVudihbZW52XSkgLi18RW52aXJvbm1lbnR8IENsb3VkRm9ybWF0aW9uXG4gICAgICAgICAgICBDUFN2Yyhbc3ZjXSkgLi18VGFzayBkZWZpbml0aW9ufCBDbG91ZEZvcm1hdGlvblxuICAgICAgICAgICAgQ1BKb2IoW2pvYl0pIC4tfFRhc2sgZGVmaW5pdGlvbnwgQ2xvdWRGb3JtYXRpb25cbiAgICAgICAgICAgIENQVGFzayhbdGFza10pIC4tfFRhc2sgZGVmaW5pdGlvbnwgQ2xvdWRGb3JtYXRpb25cbiAgICAgICAgICAgIENQUGlwZWxpbmUoW3BpcGVsaW5lXSkgLi18Q0lDRCBJbnN0cnVjdGlvbnN8IENsb3VkRm9ybWF0aW9uXG4gICAgICAgIGVuZFxuICAgIGVuZCIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6ZmFsc2UsImF1dG9TeW5jIjp0cnVlLCJ1cGRhdGVEaWFncmFtIjpmYWxzZX0)](https://mermaid-js.github.io/mermaid-live-editor/edit/#eyJjb2RlIjoiZ3JhcGggTFJcbiAgICBcbiAgICBzdWJncmFwaCBBbWF6b24gV2ViIFNlcnZpY2VzXG5cbiAgICAgICAgc3ViZ3JhcGggQ2xvdWQgU2VydmljZXNcbiAgICAgICAgICAgIFxuICAgICAgICAgICAgXG4gICAgICAgICAgICBDbG91ZEZvcm1hdGlvbiAuLT58VGFzayBEZWZpbml0aW9uOiBlbnYsc3ZjLGpvYix0YXNrfCBFQ1NcbiAgICAgICAgICAgIFxuXG5DbG91ZEZvcm1hdGlvbiAuLT58YXBwIGFuZCBlbnYgc3RhdGVzfCBTeXN0ZW1zTWFuYWdlcihbU3lzdGVtcyBNYW5hZ2VyXSlcbiAgICAgICAgICAgIEVDUiAtLT58Q29udGFpbmVyIEltYWdlfCBFQ1NcbiAgICAgICAgZW5kXG4gICAgICAgIFxuICAgICAgICBzdWJncmFwaCBDb1BpbG90IENMSVxuICAgICAgICAgICAgQ1BBcHAoW2FwcF0pIC4tfENvbmZpZ3VyYXRpb258IENsb3VkRm9ybWF0aW9uXG4gICAgICAgICAgICBDUEVudihbZW52XSkgLi18RW52aXJvbm1lbnR8IENsb3VkRm9ybWF0aW9uXG4gICAgICAgICAgICBDUFN2Yyhbc3ZjXSkgLi18VGFzayBkZWZpbml0aW9ufCBDbG91ZEZvcm1hdGlvblxuICAgICAgICAgICAgQ1BKb2IoW2pvYl0pIC4tfFRhc2sgZGVmaW5pdGlvbnwgQ2xvdWRGb3JtYXRpb25cbiAgICAgICAgICAgIENQVGFzayhbdGFza10pIC4tfFRhc2sgZGVmaW5pdGlvbnwgQ2xvdWRGb3JtYXRpb25cbiAgICAgICAgICAgIENQUGlwZWxpbmUoW3BpcGVsaW5lXSkgLi18Q0lDRCBJbnN0cnVjdGlvbnN8IENsb3VkRm9ybWF0aW9uXG4gICAgICAgIGVuZFxuICAgIGVuZCIsIm1lcm1haWQiOiJ7XG4gIFwidGhlbWVcIjogXCJkZWZhdWx0XCJcbn0iLCJ1cGRhdGVFZGl0b3IiOmZhbHNlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6ZmFsc2V9)

### Topics

[![](https://mermaid.ink/img/eyJjb2RlIjoiZ3JhcGggTFJcbiAgICBzdWJncmFwaCBQcmUtUmVxdWlzaXRlc1xuICAgICAgICBDbG91ZChbQ2xvdWRdKSAtLS0gQ29udGFpbmVycyhbQ29udGFpbmVyc10pXG4gICAgICAgIENvbnRhaW5lcnMgLS0tIENvbnRhaW5lclJ1bnRpbWUoW0NvbnRhaW5lciBSdW50aW1lc10pXG4gICAgICAgIENvbnRhaW5lcnMgLS0tIENvbnRhaW5lclJlcG9zaXRvcnkoW0NvbnRhaW5lciBSZXBvc2l0b3J5XSlcbiAgICAgICAgQ2xvdWQgLS0tIENsb3VkTG9ncyhbQ2xvdWQgTG9nc10pXG4gICAgICAgIENsb3VkIC0tLSBDb2RlUmVwbyhbQ29kZSBSZXBvc2l0b3JpZXNdKVxuICAgICAgICBDb2RlUmVwbyAuLT4gR2l0aHViXG4gICAgICAgIENsb3VkIC0tLSBDSUNEKFtDSS9DRF0pXG4gICAgICAgIENsb3VkIC0tLSBDU00oW0Nsb3VkIFN0YXRlIE1hbmFnZW1lbnRdKVxuICAgICAgICBDbG91ZCAtLS0gQnVpbGRlcnMoW0Nsb3VkIEJ1aWxkZXJzXSlcbiAgICBlbmRcbiAgICBcbiAgICBzdWJncmFwaCBBbWF6b24gV2ViIFNlcnZpY2VzXG5cbiAgICAgICAgc3ViZ3JhcGggQ2xvdWQgU2VydmljZXNcbiAgICAgICAgICAgIENvbnRhaW5lclJ1bnRpbWUgLi0gRUNTW0VsYXN0aWMgQ29udGFpbmVyIFNlcnZpY2VdXG4gICAgICAgICAgICBDb250YWluZXJSZXBvc2l0b3J5IC4tIEVDUltFbGFzdGljIENvbnRhaW5lciBSZXBvc2l0b3J5XVxuICAgICAgICAgICAgRUNSIC0tPnxDb250YWluZXIgSW1hZ2V8IEVDU1xuICAgICAgICAgICAgQ2xvdWRMb2dzIC4tIENsb3VkV2F0Y2hbQ2xvdWRXYXRjaF1cbiAgICAgICAgICAgIENvZGVSZXBvIC4tIENvZGVDb21taXRbQ29kZSBDb21taXRdXG4gICAgICAgICAgICBDSUNEIC4tIENsb3VkRm9ybWF0aW9uW0Nsb3VkIEZvcm1hdGlvbl1cbiAgICAgICAgICAgIEJ1aWxkZXJzIC4tIENsb3VkQnVpbGRcbiAgICAgICAgICAgIFxuICAgICAgICAgICAgQ2xvdWRGb3JtYXRpb24gLi0-fGVudixzdmMsam9iLHRhc2t8IEVDU1xuICAgICAgICAgICAgXG4gICAgICAgICAgICBDbG91ZEZvcm1hdGlvbiAuLT58YnVpbGQgaW5zdHJ1Y3Rpb25zfCBDbG91ZEJ1aWxkXG4gICAgICAgICAgICBDb2RlQ29tbWl0IC4tPnxDb2RlfCBDbG91ZEJ1aWxkXG4gICAgICAgICAgICBHaXRodWIgLi0-fENvZGV8IENsb3VkQnVpbGRcbiAgICAgICAgICAgIENsb3VkQnVpbGQgLi0-fENvbnRhaW5lciBJbWFnZXwgRUNSXG4gICAgICAgICAgICBcbiAgICAgICAgICAgIENTTSAuLT4gU3lzdGVtc01hbmFnZXIoW1N5c3RlbXMgTWFuYWdlcl0pXG5cbiAgICAgICAgICAgIENsb3VkRm9ybWF0aW9uIC4tPnxsb2dzfCBDbG91ZFdhdGNoXG4gICAgICAgICAgICBFQ1MgLi0-fGxvZ3N8IENsb3VkV2F0Y2hcbiAgICAgICAgICAgIEVDUiAuLT58bG9nc3wgQ2xvdWRXYXRjaFxuICAgICAgICAgICAgQ29kZUNvbW1pdCAuLT58bG9nc3wgQ2xvdWRXYXRjaFxuICAgICAgICAgICAgQ2xvdWRCdWlsZCAuLT58bG9nc3wgQ2xvdWRXYXRjaFxuICAgICAgICAgICAgU3lzdGVtc01hbmFnZXIgLi0-fGxvZ3N8IENsb3VkV2F0Y2hcblxuICAgICAgICBlbmRcbiAgICAgICAgXG4gICAgICAgIHN1YmdyYXBoIENvUGlsb3QgQ0xJXG4gICAgICAgICAgICBDUEFwcChbYXBwXSkgLi18Q29uZmlndXJhdGlvbnwgQ1NNXG4gICAgICAgICAgICBDUEVudihbZW52XSkgLi18RW52aXJvbm1lbnR8IEVDU1xuICAgICAgICAgICAgQ1BTdmMoW3N2Y10pIC4tfFRhc2sgZGVmaW5pdGlvbnwgRUNTXG4gICAgICAgICAgICBDUEpvYihbam9iXSkgLi18VGFzayBkZWZpbml0aW9ufCBFQ1NcbiAgICAgICAgICAgIENQVGFzayhbdGFza10pIC4tfFRhc2sgZGVmaW5pdGlvbnwgRUNTXG4gICAgICAgICAgICBDUFBpcGVsaW5lKFtwaXBlbGluZV0pIC4tfENJQ0QgSW5zdHJ1Y3Rpb25zfCBDbG91ZEZvcm1hdGlvblxuICAgICAgICBlbmRcbiAgICBlbmQiLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOmZhbHNlLCJhdXRvU3luYyI6ZmFsc2UsInVwZGF0ZURpYWdyYW0iOmZhbHNlfQ)](https://mermaid-js.github.io/mermaid-live-editor/edit/#eyJjb2RlIjoiZ3JhcGggTFJcbiAgICBzdWJncmFwaCBQcmUtUmVxdWlzaXRlc1xuICAgICAgICBDbG91ZChbQ2xvdWRdKSAtLS0gQ29udGFpbmVycyhbQ29udGFpbmVyc10pXG4gICAgICAgIENvbnRhaW5lcnMgLS0tIENvbnRhaW5lclJ1bnRpbWUoW0NvbnRhaW5lciBSdW50aW1lc10pXG4gICAgICAgIENvbnRhaW5lcnMgLS0tIENvbnRhaW5lclJlcG9zaXRvcnkoW0NvbnRhaW5lciBSZXBvc2l0b3J5XSlcbiAgICAgICAgQ2xvdWQgLS0tIENsb3VkTG9ncyhbQ2xvdWQgTG9nc10pXG4gICAgICAgIENsb3VkIC0tLSBDb2RlUmVwbyhbQ29kZSBSZXBvc2l0b3JpZXNdKVxuICAgICAgICBDb2RlUmVwbyAuLT4gR2l0aHViXG4gICAgICAgIENsb3VkIC0tLSBDSUNEKFtDSS9DRF0pXG4gICAgICAgIENsb3VkIC0tLSBDU00oW0Nsb3VkIFN0YXRlIE1hbmFnZW1lbnRdKVxuICAgICAgICBDbG91ZCAtLS0gQnVpbGRlcnMoW0Nsb3VkIEJ1aWxkZXJzXSlcbiAgICBlbmRcbiAgICBcbiAgICBzdWJncmFwaCBBbWF6b24gV2ViIFNlcnZpY2VzXG5cbiAgICAgICAgc3ViZ3JhcGggQ2xvdWQgU2VydmljZXNcbiAgICAgICAgICAgIENvbnRhaW5lclJ1bnRpbWUgLi0gRUNTW0VsYXN0aWMgQ29udGFpbmVyIFNlcnZpY2VdXG4gICAgICAgICAgICBDb250YWluZXJSZXBvc2l0b3J5IC4tIEVDUltFbGFzdGljIENvbnRhaW5lciBSZXBvc2l0b3J5XVxuICAgICAgICAgICAgRUNSIC0tPnxDb250YWluZXIgSW1hZ2V8IEVDU1xuICAgICAgICAgICAgQ2xvdWRMb2dzIC4tIENsb3VkV2F0Y2hbQ2xvdWRXYXRjaF1cbiAgICAgICAgICAgIENvZGVSZXBvIC4tIENvZGVDb21taXRbQ29kZSBDb21taXRdXG4gICAgICAgICAgICBDSUNEIC4tIENsb3VkRm9ybWF0aW9uW0Nsb3VkIEZvcm1hdGlvbl1cbiAgICAgICAgICAgIEJ1aWxkZXJzIC4tIENsb3VkQnVpbGRcbiAgICAgICAgICAgIFxuICAgICAgICAgICAgQ2xvdWRGb3JtYXRpb24gLi0-fGVudixzdmMsam9iLHRhc2t8IEVDU1xuICAgICAgICAgICAgXG4gICAgICAgICAgICBDbG91ZEZvcm1hdGlvbiAuLT58YnVpbGQgaW5zdHJ1Y3Rpb25zfCBDbG91ZEJ1aWxkXG4gICAgICAgICAgICBDb2RlQ29tbWl0IC4tPnxDb2RlfCBDbG91ZEJ1aWxkXG4gICAgICAgICAgICBHaXRodWIgLi0-fENvZGV8IENsb3VkQnVpbGRcbiAgICAgICAgICAgIENsb3VkQnVpbGQgLi0-fENvbnRhaW5lciBJbWFnZXwgRUNSXG4gICAgICAgICAgICBcbiAgICAgICAgICAgIENTTSAuLT4gU3lzdGVtc01hbmFnZXIoW1N5c3RlbXMgTWFuYWdlcl0pXG5cbiAgICAgICAgICAgIENsb3VkRm9ybWF0aW9uIC4tPnxsb2dzfCBDbG91ZFdhdGNoXG4gICAgICAgICAgICBFQ1MgLi0-fGxvZ3N8IENsb3VkV2F0Y2hcbiAgICAgICAgICAgIEVDUiAuLT58bG9nc3wgQ2xvdWRXYXRjaFxuICAgICAgICAgICAgQ29kZUNvbW1pdCAuLT58bG9nc3wgQ2xvdWRXYXRjaFxuICAgICAgICAgICAgQ2xvdWRCdWlsZCAuLT58bG9nc3wgQ2xvdWRXYXRjaFxuICAgICAgICAgICAgU3lzdGVtc01hbmFnZXIgLi0-fGxvZ3N8IENsb3VkV2F0Y2hcblxuICAgICAgICBlbmRcbiAgICAgICAgXG4gICAgICAgIHN1YmdyYXBoIENvUGlsb3QgQ0xJXG4gICAgICAgICAgICBDUEFwcChbYXBwXSkgLi18Q29uZmlndXJhdGlvbnwgQ1NNXG4gICAgICAgICAgICBDUEVudihbZW52XSkgLi18RW52aXJvbm1lbnR8IEVDU1xuICAgICAgICAgICAgQ1BTdmMoW3N2Y10pIC4tfFRhc2sgZGVmaW5pdGlvbnwgRUNTXG4gICAgICAgICAgICBDUEpvYihbam9iXSkgLi18VGFzayBkZWZpbml0aW9ufCBFQ1NcbiAgICAgICAgICAgIENQVGFzayhbdGFza10pIC4tfFRhc2sgZGVmaW5pdGlvbnwgRUNTXG4gICAgICAgICAgICBDUFBpcGVsaW5lKFtwaXBlbGluZV0pIC4tfENJQ0QgSW5zdHJ1Y3Rpb25zfCBDbG91ZEZvcm1hdGlvblxuICAgICAgICBlbmRcbiAgICBlbmQiLCJtZXJtYWlkIjoie1xuICBcInRoZW1lXCI6IFwiZGVmYXVsdFwiXG59IiwidXBkYXRlRWRpdG9yIjpmYWxzZSwiYXV0b1N5bmMiOmZhbHNlLCJ1cGRhdGVEaWFncmFtIjpmYWxzZX0)





### Copilot App Map

[![](/copilotappmap.png)](/copilotappmap.png)