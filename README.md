# Public CD of SMPTE 2067-204

## General

_This repository is *public*._

Please consult [CONTRIBUTING.md](./CONTRIBUTING.md), [CONFIDENTIALITY.md](./CONFIDENTIALITY.md), [LICENSE.md](./LICENSE.md) and
[PATENTS.md](./PATENTS.md) for important notices.

Your feedback is welcome at _link to GitHub issue tracker_ or at _TC chair email address_.

## Public Committee Draft (PCD) Notice

The following elements are made available for a public review period ending no earlier than 2024-01-08, and no later than 2024-08-08:

* [PCD SMPTE ST 2067-204](https://github.com/SMPTE/st2067-204/blob/main/35PM-PCD-ST-2067-204-ADM-Audio-Plugin-20230802.pdf)
* [Element a - Schema XSD](https://github.com/SMPTE/st2067-204/blob/main/35PM-CD-ST-2067-204a-ADM-Audio-Plugin-20230606.xsd)

## Details

SMPTE ST 2067-204: Interoperable Master Format – Audio with ADM Metadata Plug-in – Public Committee Draft (Public CD)

Audio Definition Model (ADM) metadata is specified in Recommendation ITU-R BS.2076. It provides an open, common metadata model that can describe channel-, object-, and scene-based audio to enable immersive and interactive experiences for broadcasting and cinema.

SMPTE ST 2067-204 specifies a plug-in mechanism to add audio with ADM metadata to IMF Compositions, utilizing the ADM MXF mapping specified in SMPTE ST 2131. The plug-in complements the "Audio with Frame-based S-ADM Metadata Plug-in" defined by SMPTE ST 2067-203. Both plug-ins are designed to be as similar as possible to aid with interchange and conversion between the formats.

Today in many post-produced audio workflows ADM metadata is carried in BW64 files along with PCM audio (Recommendation ITU-R BS.2088). Such files can be converted easily to the IMF Track Files defined in SMPTE ST 2067-204, allowing the content to be included in IMF Compositions. As such, the ADM-described content can be properly synchronized with related components (such as video), and can be managed, processed, versioned, and archived by IMF systems and workflows.

A Public Committee Draft of SMPTE ST 2067-204 is being provided for review on GitHub for at least six months from 2023-08-08. Developers are encouraged to implement the design and provide feedback via GitHub to improve the document and to increase interoperability between implementations.
