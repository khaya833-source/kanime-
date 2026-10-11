<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>K Anime - Streaming & Source Index</title>
    <style>
        :root {
            --bg-color: #0f172a;
            --card-bg: #1e293b;
            --text-color: #f8fafc;
            --accent-color: #38bdf8;
            --accent-hover: #0ea5e9;
        }
        body {
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            margin: 0;
            padding: 2rem;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .container {
            max-width: 900px;
            width: 100%;
        }
        header {
            text-align: center;
            margin-bottom: 2rem;
        }
        h1 {
            color: var(--accent-color);
            margin-bottom: 0.5rem;
        }
        p {
            color: #94a3b8;
        }
        .card {
            background-color: var(--card-bg);
            border-radius: 12px;
            padding: 1.5rem;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
        }
        .file-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 1rem;
            list-style: none;
            padding: 0;
            margin: 0;
        }
        .file-item a {
            display: block;
            background: #0f172a;
            color: var(--accent-color);
            padding: 0.75rem 1rem;
            border-radius: 8px;
            text-decoration: none;
            transition: all 0.2s ease;
            border: 1px solid #334155;
            white-space: nowrap;
            overflow: hidden;
            text-overflow: ellipsis;
        }
        .file-item a:hover {
            background: var(--accent-color);
            color: var(--bg-color);
            border-color: var(--accent-color);
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>K Anime Hub</h1>
            <p>Self-contained GitHub Pages Index & Repository Files</p>
        </header>
        
        <div class="card">
            <h3 style="margin-top: 0; border-bottom: 1px solid #334155; padding-bottom: 0.75rem;">Repository Modules</h3>
            <ul class="file-grid">
                <li class="file-item"><a href="Kanime.ts">Kanime.ts</a></li>
                <li class="file-item"><a href="agents.md">agents.md</a></li>
                <li class="file-item"><a href="allGenres.controller.ts">allGenres.controller.ts</a></li>
                <li class="file-item"><a href="anime.ts">anime.ts</a></li>
                <li class="file-item"><a href="app.ts">app.ts</a></li>
                <li class="file-item"><a href="axiosInstance.ts">axiosInstance.ts</a></li>
                <li class="file-item"><a href="bug_report.md">bug_report.md</a></li>
                <li class="file-item"><a href="characterDetail.controller.ts">characterDetail.controller.ts</a></li>
                <li class="file-item"><a href="characters.controller.ts">characters.controller.ts</a></li>
                <li class="file-item"><a href="comprehensive.test.ts">comprehensive.test.ts</a></li>
                <li class="file-item"><a href="config.ts">config.ts</a></li>
                <li class="file-item"><a href="detailpage.controller.ts">detailpage.controller.ts</a></li>
                <li class="file-item"><a href="episodes.controller.ts">episodes.controller.ts</a></li>
                <li class="file-item"><a href="errors.ts">errors.ts</a></li>
                <li class="file-item"><a href="eslint.config.js">eslint.config.js</a></li>
                <li class="file-item"><a href="extractCharacterDetail.ts">extractCharacterDetail.ts</a></li>
                <li class="file-item"><a href="extractCharacters.ts">extractCharacters.ts</a></li>
                <li class="file-item"><a href="extractDetailpage.ts">extractDetailpage.ts</a></li>
                <li class="file-item"><a href="extractEpisodes.ts">extractEpisodes.ts</a></li>
                <li class="file-item"><a href="extractHomepage.ts">extractHomepage.ts</a></li>
                <li class="file-item"><a href="extractListpage.ts">extractListpage.ts</a></li>
                <li class="file-item"><a href="extractNews.ts">extractNews.ts</a></li>
                <li class="file-item"><a href="extractNextEpisodeSchedule.ts">extractNextEpisodeSchedule.ts</a></li>
                <li class="file-item"><a href="extractSchedule.ts">extractSchedule.ts</a></li>
                <li class="file-item"><a href="extractServers.ts">extractServers.ts</a></li>
                <li class="file-item"><a href="extractSuggestions.ts">extractSuggestions.ts</a></li>
                <li class="file-item"><a href="extractTopSearch.ts">extractTopSearch.ts</a></li>
                <li class="file-item"><a href="feature_request.md">feature_request.md</a></li>
                <li class="file-item"><a href="filter.controller.ts">filter.controller.ts</a></li>
                <li class="file-item"><a href="filter.ts">filter.ts</a></li>
                <li class="file-item"><a href="handler.ts">handler.ts</a></li>
                <li class="file-item"><a href="homepage.controller.ts">homepage.controller.ts</a></li>
                <li class="file-item"><a href="index.ts">index.ts</a></li>
                <li class="file-item"><a href="jest.config.ts">jest.config.ts</a></li>
                <li class="file-item"><a href="listpage.controller.ts">listpage.controller.ts</a></li>
                <li class="file-item"><a href="mocks.ts">mocks.ts</a></li>
                <li class="file-item"><a href="news.controller.ts">news.controller.ts</a></li>
                <li class="file-item"><a href="nextEpisodeSchedule.controller.ts">nextEpisodeSchedule.controller.ts</a></li>
                <li class="file-item"><a href="package.json">package.json</a></li>
                <li class="file-item"><a href="package.yml">package.yml</a></li>
                <li class="file-item"><a href="random.controller.ts">random.controller.ts</a></li>
                <li class="file-item"><a href="release.yml">release.yml</a></li>
                <li class="file-item"><a href="response.ts">response.ts</a></li>
                <li class="file-item"><a href="routes.ts">routes.ts</a></li>
                <li class="file-item"><a href="schedules.controller.ts">schedules.controller.ts</a></li>
                <li class="file-item"><a href="search.controller.ts">search.controller.ts</a></li>
                <li class="file-item"><a href="servers.controller.ts">servers.controller.ts</a></li>
                <li class="file-item"><a href="suggestion.controller.ts">suggestion.controller.ts</a></li>
                <li class="file-item"><a href="topSearch.controller.ts">topSearch.controller.ts</a></li>
                <li class="file-item"><a href="tsconfig.json">tsconfig.json</a></li>
                <li class="file-item"><a href="vercel.json">vercel.json</a></li>
                <li class="file-item"><a href="vitest.config.ts">vitest.config.ts</a></li>
            </ul>
        </div>
    </div>
</body>
</html>