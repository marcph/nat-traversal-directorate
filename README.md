Proposed NAT Traversal Directorate
==================================================

(Note that most of the text is taken from various existing charters, and especially from the TSV area Directory charter)

The NAT traversal directorate is an advisory group of NAT traversal experts.
The notion of a directorate is defined in RFC 2418 as follows:

```
In many areas, the area directors have formed an advisory group or directorate. These comprise
experienced members of the IETF and the technical community represented by the area. The specific
name and the details of the role for each group differ from area to area, but the primary intent
is that these groups assist the area director(s), e.g., with the review of specifications produced
in the area."
```

The directorate is best thought of as a convenient way to contact a group of NAT traversal experts within the IETF.

The area directors invite WG chairs and other qualified individuals to participate in the directorate, to take advantage of their expertise in NAT traversal related fields.
Individuals who wish to join the directorate should contact an area director.

# Activities

The area directors use the feedback from the directorate when making decisions on a range of topics related to NAT traversal.
The area directors might consult the directorate for the following activities:

- Review of selected documents within the transport area, usually during working group last call. 

- Review of selected documents from other areas of the IETF, usually during IETF last call or IESG Evaluation. 

- Review of proposals for BOFs, for creation of new WGs, and for revised charters. 

- Cross-area technical advice, possibly serving as informal or formal technical advisors in working groups in the transport area or other areas in the IETF. 

- Cross-SDO technical advice, contributing their expertise to transport-related liaison work with other standards organizations. 

As with all IETF activities, participation is a volunteer effort, so members are free to decline any request from the area directors.

# Directorate Reviews

The directorate is not a formal review body; the IESG has that role.
Therefore, comments made by the directorate have no more weight than those made by individual IETF participants.

## Review Requests

The ADs generally assign directorate reviews to individual directorate members.

We use an automated round-robin approach to assigning reviews such that everyone completes roughly the same number of reviews, but may deviate from that when special review is desired.

Review is typically done at IETF Last Call, when the document appears on the IESG agenda, or both.
In addition, some documents are reviewed earlier based on a request from the AD.

## Review Format

TSV directorate reviews should begin with this paragraph:

```
I've reviewed this document as part of the NAT traversal directorate's ongoing effort to review
key IETF documents. These comments were written primarily for area directors, but are copied to
the document's authors for their information and to allow them to address any issues raised.
When done at the time of IETF Last Call, the authors should consider this review together with
any other last-call comments they receive. Please always CC <tbd>-dir@ietf.org if you reply to
or forward this review.
```

Generally, NAT traversal directorate reviews should especially focus on transport-related issues.
However, reviewers are of course free to raise any issue they deem important, transport-related or not.

Each review should include a summary statement chosen from or adapted from the following list:

- This draft is ready for publication as a [type] RFC, where [type] is Informational, Experimental, etc.
(In some cases, the review might recommend publication as a different [type] than requested by the author.)
- This draft is basically ready for publication, but has nits that should be fixed before publication.
- This draft is on the right track but has open issues, described in the review.
- This draft has serious issues, described in the review, and needs to be rethought.
- This draft has very fundamental issues, described in the review, and further work is not recommended.
- Unfortunately, I don't have the expertise to review this draft. 

Also, please take a look at the Gen-ART review guidelines at http://www.alvestrand.no/ietf/gen/art/review-guidelines.html.

## Review Submission

The NAT traversal directorate reviewer sends a completed review by email.
The review should be CC'ed to the NAT traversal directorate mailing list at &lt;tbd&gt;-dir@ietf.org.
The suggested subject line for transport directorate reviews is:

```
Subject: <tbd>-dir review of draft-name-here-end-with-version-number-00
```

1. For a document during IETF Last Call, as a regular last-call comment, i.e., send to ietf@ietf.org or, in exceptional cases, to iesg@ietf.org.
It is recommended to also CC the mailing list of the working group that has produced the document &lt;wg&gt;@ietf.org, or, for individual submissions, the authors directly. 

1. For a document from a WG during IESG Review, to iesg@ietf.org.
It is recommended to also CC the mailing list of the working group that has produced the document, or, for individual submissions, the authors directly. 

1. For documents for which an early review has been requested, to the WG that requested the early review. 

## Review Common Issues

NAT traversal common issues describes some issues that have come up during reviews, and guidelines to provide authors about how to resolve them.
This is documented so NAT tarversal reviewers are fairly consistent in their advice.

### Multiplexing

NAT traversal often require sharing the same source ports between different protocols.
Reviewers should carefully evaluate how the multiplexing is done.

## Review Status

http://tools.ietf.org/tools/art/tbddir/index.cgi holds the current review assignments to directorate members with the respective due dates.
Review Tool has a description of the various screens and fields.
Many of the column and row titles can be clicked on to get a help popup. 

# Current Members

The current directorate members, together with any formal function they have on behalf of the directorate, are:

Name | Function
---- | --------
Marc Petit-Huguenin |
Simon Perreault |

Individuals who wish to join the directorate should contact an area directors.

# Mailing List

The transport directorate mainly operates via the mailing list at http://www.ietf.org/mailman/listinfo/tbd-dir.
This is a private list for the members and ADs.

