** Row Level Security (RLS) ** was implemented to enforce least-privilege access for anonymous users.  
Insert operations are permitted without identity verification to ensure user safety,  
while read access is restricted to recent, non-expired reports to mitigate mass data scraping and  
long-term exposure risks.  
  
This layered security approach ensures that even if API credentials are compromised, sensitive data remains protected.
