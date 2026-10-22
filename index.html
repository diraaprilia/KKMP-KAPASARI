-- Prototype Koperasi demo: satu baris menyimpan seluruh data aplikasi.
-- PERINGATAN: kebijakan ini mengizinkan siapa pun yang memiliki URL dan anon key
-- membaca/mengubah data demo. Jangan gunakan untuk data koperasi yang sebenarnya.

create table if not exists public.kdmp_state (
  id integer primary key check (id = 1),
  data jsonb not null,
  updated_at timestamptz not null default now()
);

alter table public.kdmp_state enable row level security;

grant usage on schema public to anon;
grant select, insert, update on public.kdmp_state to anon;

drop policy if exists "demo can read state" on public.kdmp_state;
create policy "demo can read state"
on public.kdmp_state
for select
to anon
using (true);

drop policy if exists "demo can insert state" on public.kdmp_state;
create policy "demo can insert state"
on public.kdmp_state
for insert
to anon
with check (id = 1);

drop policy if exists "demo can update state" on public.kdmp_state;
create policy "demo can update state"
on public.kdmp_state
for update
to anon
using (id = 1)
with check (id = 1);
