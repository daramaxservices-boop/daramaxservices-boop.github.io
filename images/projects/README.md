# Project Photos — how to add them

Drop the real job photos into these folders. The website's portfolio section
on the homepage loads them automatically — no code changes needed.

## Folder layout

images/projects/exterior/   → outdoor work (facades, landscaping, driveways, awnings, roofing)
images/projects/interior/   → indoor work (kitchens, bathrooms, basements, offices, stairs, bars, full-home)

## File names the site looks for

Homepage portfolio tiles try these files (in this order of preference):

| Tile       | File to drop in                                              |
|------------|--------------------------------------------------------------|
| Exterior   | images/projects/exterior/exterior-1.jpg                      |
| Interior   | images/projects/interior/interior-1.jpg                      |
| Kitchen    | images/projects/interior/kitchen-1.jpg                       |
| Bathroom   | images/projects/interior/bathroom-1.jpg                      |
| Basement   | images/projects/interior/basement-1.jpg                      |
| Garage     | images/projects/interior/garage-1.jpg                        |
| Living Room| images/projects/interior/living-room-1.jpg                   |
| Office     | images/projects/interior/office-1.jpg                        |
| Stairs     | images/projects/interior/stairs-1.jpg                        |
| Bar        | images/projects/interior/bar-1.jpg                           |
| Full Home  | images/projects/interior/full-home-1.jpg                     |

Want more than one photo per tile? Add `-2`, `-3`, … (e.g. `kitchen-2.jpg`)
and tell me — I'll wire the extra slots in.

## Rules

- Formats: `.jpg`, `.jpeg`, `.png`, or `.webp` (WebP preferred)
- Keep each file under ~200 KB — compress before uploading (e.g. Squoosh.app)
- Landscape orientation works best (tiles are wide)
- Name files descriptively, e.g. `kitchen-renovation-scarborough-daramax.jpg`
  also works — just let me know the name so I can point the tile at it
- Until a photo exists, the tile shows a styled placeholder with the
  category label, so the page never looks broken

## Alt text (for Google)

Every photo gets alt text in this pattern:
"[what it is] in [city] by Daramax Services"
e.g. "Kitchen renovation in Scarborough by Daramax Services"
