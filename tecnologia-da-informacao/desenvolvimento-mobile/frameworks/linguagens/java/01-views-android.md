---
titulo: Views no Android
---
- [Manipulando Views No Android]([https://developer.android.com/guide/components/activities/intro-activities?hl=pt-br](https://blog.matheuscastiglioni.com.br/manipulando-views-no-android/)): Sabemos que ficar procurando views (elementos ou componentes) no Android é um tanto quanto chato, necessitamos muitas linhas de código para realizar muito pouco.

# Views no Android

## Criando a view

~~~xml
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_height="match_parent"
    android:gravity="center_horizontal"
    android:orientation="vertical"
    android:padding="10dp"
    android:layout_width="match_parent"
    tools:context="blog.matheuscastiglioni.com.br.injetando_views.MainActivity">

    <EditText
        android:layout_height="wrap_content"
        android:id="@+id/et_nome"
        android:hint="Digite seu nome"
        android:textSize="20dp"
        android:layout_width="match_parent"/>

    <Button
        android:layout_height="wrap_content"
        android:id="@+id/btn_ola"
        android:layout_margin="20dp"
        android:text="Ola"
        android:layout_width="wrap_content"/>

    <TextView
        android:layout_height="wrap_content"
        android:id="@+id/tv_nome"
        android:textAlignment="center"
        android:textSize="30dp"
        android:layout_width="match_parent"/>

</LinearLayout>
~~~

## Referência do objeto

~~~java
Button btnOla = findViewById(R.id.btn_ola);
~~~

## Evento

~~~java
Button btnOla = findViewById(R.id.btn_ola);

btnOla.setOnClickListener(new View.OnClickListener() {
	@Override
	public void onClick(View view) {
		// aqui executamos uma determinada função ou um trecho de código    
	}
});
~~~

## Setando valores 

~~~java
EditText etNome = findViewById(R.id.et_nome);
TextView tvNome = findViewById(R.id.tv_nome);

String nome = etNome.getText().toString();
tvNome.setText("Olá " + nome);
~~~
