### Hi there :wave:

I'm Andreas Gohr, welcome to my github profile. I'm a web developer and maker living in Berlin, Germany. You probably know me from my work on [DokuWiki](https://github.com/splitbrain/dokuwiki), but you'll find all kinds of other projects here. Check the links below to get started.

#### :hammer: Check out what I'm currently working on

These are the projects I most recently contributed to.

{{range recentContributions 10}}
- [{{.Repo.Name}}]({{.Repo.URL}}) - {{.Repo.Description}} ({{humanize .OccurredAt}})
{{- end}}

#### :scroll: My recent blog posts

I blog at [splitbrain.org](https://www.splitbrain.org) for nearly two decades now. Here is what I have published recently.

{{range rss "https://www.splitbrain.org/feed/blog" 5}}
- [{{.Title}}]({{.URL}}) ({{humanize .PublishedAt}})
{{- end}}

#### :hearts:️ These awesome people sponsor me (thank you!)

If you like what I'm doing, you can [sponsor me on github](https://github.com/sponsors/splitbrain). These fine people already do.

{{range sponsors 20}}
- [{{.User.Login}}]({{.User.URL}}) ({{humanize .CreatedAt}})
{{- end}}
