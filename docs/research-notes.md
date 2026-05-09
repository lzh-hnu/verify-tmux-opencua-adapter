# Verify tmux for OpenCUA: Open Session Interface

A verification page for an OpenCUA adapter that exposes terminal sessions through tmux.

## Verification Focus

- Agent: OpenCUA
- Track: Adapter Verification
- Shared image: `docs/assets/hero.png`
- Image position: fixed in the right-side hero media container

## Trace Notes

- Pane metadata is exposed without hiding terminal provenance.
- Resize and focus events are normalized before interpretation.
- Adapter responses include recoverable state markers.

## Review Lens

- Interface clarity
- Portability across shells
- Recoverable state exposure
