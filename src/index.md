<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tiger Knowledge Base</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body { font: 16px/1.5 system-ui, -apple-system, sans-serif; background: #fafafa; color: #333; }
    .container { max-width: 900px; margin: 0 auto; padding: 20px; }
    h1 { font-size: 2.5rem; margin-bottom: 0.5rem; color: #1a1a1a; }
    .subtitle { color: #666; margin-bottom: 2rem; }
    .search-box { position: sticky; top: 0; background: #fafafa; padding: 1rem 0; z-index: 100; }
    .search-input { width: 100%; padding: 14px 20px; font-size: 1.1rem; border: 2px solid #ddd; border-radius: 8px; outline: none; }
    .search-input:focus { border-color: #ff6b35; }
    .categories { display: flex; flex-wrap: wrap; gap: 8px; margin-bottom: 2rem; }
    .cat-btn { padding: 6px 14px; background: #fff; border: 1px solid #ddd; border-radius: 20px; cursor: pointer; font-size: 0.9rem; }
    .cat-btn.active { background: #ff6b35; color: #fff; border-color: #ff6b35; }
    .results { display: grid; gap: 16px; }
    .result { background: #fff; padding: 20px; border-radius: 8px; border: 1px solid #eee; }
    .result h3 { color: #ff6b35; margin-bottom: 0.5rem; }
    footer { margin-top: 40px; padding: 20px; text-align: center; color: #999; }
  </style>
</head>
<body>
  <div class="container">
    <h1>🐯 Tiger Knowledge Base</h1>
    <p class="subtitle">52 articles on tiger biology, conservation, subspecies, and culture</p>
    <div class="categories">
      <button class="cat-btn active">All</button>
      <button class="cat-btn">Biology</button>
      <button class="cat-btn">Behavior</button>
      <button class="cat-btn">Conservation</button>
      <button class="cat-btn">Culture</button>
      <button class="cat-btn">Subspecies</button>
    </div>
    <div class="results">
      <div class="result"><h3>Browse by Category</h3><p>Select a category above to explore 52 articles across 11 topics.</p></div>
    </div>
  </div>
  <footer><p>Tiger Knowledge Base • Powered by domstack</p></footer>
</body>
</html>