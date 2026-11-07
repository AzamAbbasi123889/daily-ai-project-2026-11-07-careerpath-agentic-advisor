# Implementation Checklist

Build the application yourself using `PROJECT_BRIEF.md`.

## Initial setup

- [ ] Read the project specification.
- [ ] Review the architecture and data model.
- [ ] Create a Python virtual environment.
- [ ] Install and pin the required dependencies.
- [ ] Configure credentials through environment variables.
- [ ] Review the data privacy and security requirements.

## Project acceptance criteria

- [ ] API returns 200 with stored user_id
- [ ] Data persisted in Postgres with a generated embedding vector
- [ ] Validation errors returned for missing fields
- [ ] Job posting pipeline runs nightly via GitHub Actions
- [ ] >95% of postings have non‑null embedding vectors
- [ ] Embeddings indexed in pgvector and searchable
- [ ] Response includes at least 5 roadmap steps
- [ ] Each step lists skill, resource URL, and estimated weeks
- [ ] Overall confidence score >0.7 for the generated plan
- [ ] Set up FastAPI skeleton
- [ ] Create Postgres schema with pgvector
- [ ] Implement job‑posting ingestion script (Kaggle dataset)
- [ ] Write unit tests for data layer
- [ ] Unit test each FastAPI endpoint with pytest and httpx
- [ ] Integration test LangGraph state transitions using mock LLM responses
- [ ] Contract test vector similarity queries (FAISS‑like behavior)
- [ ] Load test GET /roadmap with 100 concurrent users (locust)
- [ ] Containerize API, Redis, Postgres using Docker Compose
- [ ] Deploy to Railway or Render free tier for MVP
- [ ] Configure GitHub Actions to build, test, and push Docker images
- [ ] Enable HTTPS via automatic Let’s Encrypt

## Before completion

- [ ] Implement the planned MVP features.
- [ ] Add unit and integration tests.
- [ ] Run the test suite.
- [ ] Measure the evaluation metrics in the brief.
- [ ] Record actual results and known limitations.
- [ ] Document setup and deployment.
- [ ] Update the README to reflect the implemented features.
- [ ] Add only verified outcomes to your resume.
