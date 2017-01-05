# Server role
- Consul
- Scheduler
- Internal API (Server <-> Worker)
- External API (Web interface + SABnzbd/NZBGet/CouchPotato integration)
- DB suppoort (mongo)
- Search support (Sphinx or ELK)
- Caching

# Worker role
- Consul
- Internal API (Server <-> Worker)
- NNTP pulls
- Processing/cleanup/info grapping
- External data providers
