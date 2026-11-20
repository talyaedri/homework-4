# Curious Minds Club Chatbot

Open [the notebook in Google Colab](https://colab.research.google.com/github/talyaedri/homework-4/blob/main/club_chatbot.ipynb) after the notebook has been pushed to the repository and access has been granted.

1. Create a Supabase project and copy its **session pooler** PostgreSQL URI, substituting the database password locally.
2. In Colab Secrets (key icon), add `OPENAI_API_KEY` and `SUPABASE_DB_URL` and enable notebook access to both. Never paste either value into the notebook or GitHub.
3. Run all cells in order. Inspect the graph and test replies, then use the Gradio interface. Stop the Gradio cell when finished and do not publish its share link.
4. Restart the Colab runtime, rerun the cells, reopen a saved conversation and check that both topic and messages were restored. Inspect Supabase checkpoint tables and write the required reflection based on your own observations.

The prompt is in [prompt.md](prompt.md). The system-message guard is probabilistic, so test off-topic and mixed-topic prompts and refine it when needed.
