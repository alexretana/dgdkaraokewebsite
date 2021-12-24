# dgdkaraokewebsite
Silly Website to play DGD with subtitles

## Software Stack
### Frontend
- W3CSS (styling)
- TypeScript
- Maybe Petite Vue if needed?

#### TODO:
- [ ] Create Tests For Frontend


### Backend
- [PyonFx](https://pyonfx.readthedocs.io/en/latest/): Create Karaoke Effects
- [ffsubsync](https://github.com/smacke/ffsubsync): Sync Subtitles with Audio
- flask

#### TODO:
- [ ] Use jupyter notebook to create Subtitles for karaoke
- [ ] Create Tests For Backend with the following behaviors:
  - [ ] Stream From Azure Blob Storage to Client

### Database
- Azure Storage for .mp4's
- FileSystem Should suffice

#### TODO:
- [ ] Download DGD music, including instumental
- [ ] Put into Azure Blob Storage
