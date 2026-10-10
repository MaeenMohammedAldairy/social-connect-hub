<!-- LOVABLE:BEGIN -->
> [!IMPORTANT]
> This project is connected to [Lovable](https://lovable.dev). Avoid rewriting
> published git history — force pushing, or rebasing/amending/squashing commits
> that are already pushed — as it rewrites history on Lovable's side and the
> user will likely lose their project history.
>
> Commits you push to the connected branch sync back to Lovable and show up in
> the editor, so keep the branch in a working state.
<!-- LOVABLE:END -->

- Preserve the TanStack Start bootstrap and original public routes when importing projects; hosting owns route generation.
- Keep verified platform connections server-controlled and read-only to browser users; client UI never creates a successful connection.
- Use one account provider for session transitions and connection state; keep private saved settings and content reviews in Cloud with owner-scoped policies.
- Keep responsive MenaFlow layout and visual tokens in the global stylesheet, with no phone-simulator frames.
