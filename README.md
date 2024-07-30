# Foresight

Full Stack Role:

- Clone [Glean](https://www.glean.com/) - enterprise search (you can search through slack, notion, gdrive, gmail in one app)
    - Specific Instructions
        - Glean is a web app where you can connect to slack, notion, gmail, jira etc. and then search over documents with AI
        - Pick one source (slack, notion, gmail) and build an MVP of what this could look like UI attached below

AI Role:

- Clone [Apten](https://www.apten.ai/) / [Ada](https://www.ada.cx/) — AI agent builder with rule following.
    - Specific instructions
        - Apten and Ada are no-code platforms to build AI agents for messaging.
        - They contain the following features (make a trial account on ada to see all features)
            - collecting dynamic information
            - RAG
            - function calling etc.
        - Per [this video](https://video.wixstatic.com/video/ff3beb_361d2f547d53412c87099c902435128a/720p/mp4/file.mp4) and the above components build a prompt framework that encompasses the high level components (to dynamically collect and store information).
            - You must not just use raw hardcoded english in prompt — think about how platforms like these do it
    - No frontend needed, but implement API endpoints that would be realistic returning this entire graph
    - For testing, implement a basic a sales agent which collects all relevant information, can answer questions about a product / business, follows up and saves information in database
    - Record video of this working
