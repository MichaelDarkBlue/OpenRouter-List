# OpenRouter-List
# OpenRouter Model Browser

A lightweight HTML/JavaScript page that displays available AI models from [OpenRouter.ai](https://openrouter.ai/) with **live filtering**, **price filtering**, **name search**, and **model browsing**.

Built with:
- Vanilla JavaScript (no frameworks)
- Modern **dark mode** + **neon green** theme
- No backend required — runs 100% client-side

---

## Features

- **Load Models**: Fetches the latest list of OpenRouter models once and caches them locally.
- **Filter by Cost**: Limit models by maximum prompt or completion price (per token).
- **Filter by Name**: Search and filter models live as you type.
- **Show All Models**: Override cost filtering to display every loaded model.
- **Reset Filters**: Quickly reset cost and name filters to defaults.
- **Dark Mode UI**: Sleek, neon-green outlined design with hover effects.
- **No API Key Needed**: Public models are fetched without authentication.

---

## How to Use

1. Clone or download this repository.
2. Open the `modelList.html` file in any modern web browser (Chrome, Edge, Firefox, etc.).
3. Click **Load Models** to fetch and view the model list.
4. Use the filters or search box to narrow down your results.
5. Optionally, click **Show All Models** to view everything, or **Reset Filters** to start over.

---

## File Structure

| File | Purpose |
|:----|:--------|
| `modelList.html` | Main application (HTML, CSS, JavaScript in one file). |
| `README.md` | Project overview and instructions. |

---

## Example Screenshot

> ![Screenshot Placeholder]

_(Optionally insert a screenshot here by opening the page, taking a screenshot, and linking it.)_

---

## Notes

- The model list is pulled from OpenRouter's public `/api/v1/models` endpoint.
- Data is cached after loading to avoid unnecessary repeated API calls.
- Only public model metadata is shown; no inference or completion requests are made.
- Prices are **per token**, based on prompt or output generation, not per full request.

---

## Future Improvements

- Add sorting by price, name, or context length.
- Add pagination for very large lists.
- Display provider information or additional model capabilities.
- Allow saving favorite models.

---

## License

This project is released under the **GNU License**.  
You are free to use, modify, and distribute it.

---

## Credits

- Powered by [OpenRouter.ai](https://openrouter.ai/)
- Designed and coded by [Your Name Here] (you can add your name if you like!)