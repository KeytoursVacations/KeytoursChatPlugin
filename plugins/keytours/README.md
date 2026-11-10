# Keytours

**Luxury Travel & Vacations. Your Personal Luxury Travel Planner.**

Discover, personalize and plan extraordinary journeys worldwide with Keytours Vacations, directly in Claude. The plugin connects Claude to the Keytours MCP server and adds a travel-planning skill, so Claude can build an itinerary from live Keytours availability and prices and save it as a trip plan in your Keytours account. Powered by KeyBrain.

## Example requests

- "Plan a luxury 10-day vacation to Italy."
- "Find a private guided tour in Greece."
- "Build a trip to Japan with luxury hotels."
- "Compare vacation packages in Spain."
- "Arrange a private airport transfer in Paris."

## What it does

- **Hotels**: search by destination, area or landmark, view details and facilities, and check room availability and rates.
- **Flights and trains**: search one-way and round-trip itineraries and compare fares and fare options.
- **Tours and vacation packages**: browse tours, check accommodation options and departures, or request a quote for tailor-made packages.
- **Activities**: discover experiences by destination and category and check availability for your dates.
- **Cruises**: search by region or departure port, compare sailings and choose a cabin.
- **Transfers and car rentals**: find airport and city transfers, including return trips, and rent a car.
- **Trip cart and review**: keep all selected services in one cart and review the itinerary for timing and connection issues.
- **Trip plan**: save the cart as a trip plan in your Keytours account. A trip plan is not a confirmed reservation; payment, traveler details and confirmation are completed in KeyPal.

All prices, availability and descriptions come from Keytours systems.

## Components

| Component | Description |
|---|---|
| MCP server `keytours` | Remote HTTP server at `https://mcp.keytours.com/claude` |
| Skill `plan` | Travel search and planning guidance. Run it with `/keytours:plan` |

## Sign-in

Searching and building a trip cart work without an account. When you save a trip plan, a browser window opens for you to sign in with your Keytours account (OAuth). Claude never sees your password, and the plugin stores no credentials of its own.

## Data handling

The plugin sends data only to Keytours (`mcp.keytours.com`), and only what each request needs:

- Search criteria: destinations, dates, number of travelers and children's ages.
- Services and options you add to your trip cart, and the trip name.

Traveler details and payment are not entered in Claude; they are completed in KeyPal. Keytours processes this data as described in the [Keytours Privacy Policy](https://www.keytours.com/sp/privacy-policy).

## Support

- Contact: https://www.keytours.com/sp/contact-us
- Email: info@keytours.com
- Terms & Conditions: https://www.keytours.com/sp/terms-conditions

## License

Proprietary. See [LICENSE](LICENSE).
